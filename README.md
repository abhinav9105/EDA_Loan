# Project Name
> Understand the of risk analytics in banking and financial services 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
-Background: 
 When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company 


Bussiness Problem:
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
To develop your understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).
 

Loan Dataset: It contains the complete loan data for all loans issued through the time period 2007 t0 2011.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
-Maximum loan purpose are debt_consolidation(52%)
-The majority of the loans range from 6000 to 15000
-The majority of the interest rate range from 8.9 to 14.4
-Approx 12% of loan are charged off
-maximum 10year plus person has taken loan
-Maximum person are from CA(california)who has taken the loan
Avg loan amount is charges is around 11000
Avg interest rate on which loan is charged of is around 13%
people who take loan for the purpose of moving they have less charge off(maximum chances to get loan back)
please observe the box plot between amount and status and purpose
it will tell you if loan is which about you have chance of charge off like if loann is more than 16000 and for debt_consolidation there are very less chance of loan repayment


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
numpy
pandas
seaborn
matplotlib.pyplot
warnings


## Acknowledgements
For more understanding of library please check https://seaborn.pydata.org/tutorial/introduction.


## Contact
Created by [@abhinav9105] - feel free to contact me!


