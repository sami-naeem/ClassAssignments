# Plaid Case Study

![Plaid Logo](https://plaid.com/assets/img/social-card.jpg)

## Description
* Plaid is a software company that provides API’s for application software to communicate with banks
about customer accounts via language agnostic JSON. Complicating such communications is the need to
deal with identity verification, various kinds of error conditions, and the possibility that the same
customer might have multiple accounts that need to be accessed simultaneously for aggregate balances,
etc.
Banks have much more data about customers than most of us realize, and the Plaid API can get it. Plaid
can retrieve such things as the geolocation data for a given transaction and render it into intelligible form.
As an example of the latter activity, called “cleaning”, the code “SBXUSQ0112x” would be translated as
“Starbucks Coffee, 41 Union Square, New York, New York in New York City”. The Plaid API can also
retrieve the bank’s estimates of their customer incomes!
Plaid is in the early stages of using this data to help companies make better offers to customers, so they
are just getting into data science.


    * What is the background of your company? What do they do? Who are their competitors?:
    Plaid is a software company that provides API’s for application software to communicate with banks about customer accounts via language agnostic JSON. Complicating such communications is the need to deal with identity verification, various kinds of error conditions, and the possibility that the same customer might have multiple accounts that need to be accessed simultaneously for aggregate balances, etc. Banks have much more data about customers than most of us realize, and the Plaid API can get it. Plaid can retrieve such things as the geolocation data for a given transaction and render it into intelligible form. As an example of the latter activity, called “cleaning”, the code “SBXUSQ0112x” would be translated as “Starbucks Coffee, 41 Union Square, New York, New York in New York City”. The Plaid API can also retrieve the bank’s estimates of their customer incomes! Plaid is in the early stages of using this data to help companies make better offers to customers, so they are just getting into data science.

    * Plaid's competitors and similar companies include Galileo Financial Technologies, Akoya, Finicity, Synapse, MX, N26, Codat, Xignite and Varo Money.

    * How does this company use technology to their advantage? Why are they considered a FinTech company?:
    Banks have much more data about customers than most of us realize, and the Plaid API can get it. Plaid can retrieve such things as the geolocation data for a given transaction and render it into intelligible form. Because banks are within the finance industry and Plaid's API's are extensively used within banking, this makes Plaid a FinTech company.


### Plaid Case Study Proposal
* Why This Matters
Banks do not provide an API for their customer data because there is no financial incentive or regulatory
requirement that they do so. Yet this is precisely what is needed for third party fintech companies, such as
Betterment and Venmo, who need to seamlessly link to customer bank accounts (To understand this need
better, consider PayPal’s methodology for linking to a bank account: the customer must enter the account
information onto the PayPal web page and wait a few days while PayPal deposits, and then withdraws
two amounts of less than a dollar. It is only after the customer enters the amount of those deposits that the
link with PayPal becomes operational. Not exactly seamless!).
And that is what 25% of Americans with bank accounts have asked various apps to do in 2018, up 13%
from 2017. Yes, the banks have to agree to connect with Plaid, but more than 10,000 of them do,
including the likes of JP Morgan Chase, Bank of America, CitiBank, and Wells Fargo. After Plaid’s last
funding round, its market cap is over $2.7 billion, making it a start-up “unicorn”. An initial public
offering (or IPO) in 2019 appears likely.
Why This May Be Interesting
● Since Plaid is so deeply enmeshed in the fintech ecosystem, many people are likely to use the
Plaid API, and many others will likely use similar Python-accessible API’s. Plaid itself has about
300 employees in its San Francisco location at the moment. As a recent Forbes article states,
“Plaid's founders know that they need to expand the uses of Plaid if they want to be a company
much larger than their predecessors”. In other words, they are in a “grow or die” situation, so
they will continue to hire rapidly.
● Plaid also provides the web page fin.plaid.com, which provides think pieces that take the pulse of
the current fintech scene.
Things to Keep in Mind for a Case Study
● An explanation of Plaid’s role in the fintech ecosystem
● Explanation of PayPal’s clunky account verification algorithm o Walk-through of Plaid API
mechanics as described in the Forbes article
● A demonstration of how to use Plaid’s API to grab customer data from a hypothetical bank
account (Plaid allows prospective users to try such things for free in their “sandbox”.).
Resources:
● https://plaid.com/ (Plaid website)
● https://www.inc.com/jeff-pruitt/6-fintechs-disrupting-the-industry.html (Plaid is one of these
disruptors, and this article explains more clearly than the Plaid website what Plaid actually does.).
● https://www.forbes.com/plaid-fintech/#7d07821767f9 (More detail about Plaid.).
● https://security.stackexchange.com/questions/198005/is-plaid-a-service-which-collects-user-s-ba
nking- login-information-safe-to-use (StackExchange page discussing Plaid’s security model. It
notes that banks themselves do not provide API’s to access customer data, which is the raison
d’être for Plaid).


Why is this company exemplary in the FinTech space? What are their strengths and weaknesses?
The company provides an API for their customer data, whereas Banks do not provide an API since there is no financial incentive or regulatory. 

What is the prognosis for this company? Where do they expect to be in the future?
The company is in a "grow or die situaton". Best put by a recent Forbes article "PLaid's founders know that they need to expand the uses of Plaid if they want to be a company larger than their predecessors". Most likely, the company has a bright future ahead of it since it is offering a service that is not being offered by other fintech companies.  
