# Prosper Loan Data Investigation
## by Angel Newportright


## Dataset

> Provide basic information about your dataset in this section. If you selected your own dataset, make sure you note the source of your data and summarize any data wrangling steps that you performed before you started your exploration.

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

Find the link to the data [here](https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv), with data dictionary available [here](https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0).


## Summary of Findings

In the exploration, I found that; 

1. More loans fall under debt consolidation listing category.

What this mean is that debt consolidation is the majority 
reason why people apply for loan on the prosper platform. 
i.e, majority of the loans are taken to repay smaller loans.

2. There is no relationship between monthly income and loan 
original amount.

What this means is that the monthly income of a person does 
not directly impact the amount on the loan they apply for on 
the prosper platform.

I verified the relationship between the 'Loan Original Amount', 
the 'StatedMonthlyIncome' and the 'BorrowerAPR' For the dataset 
given. There was no interaction between (i) the amont of a loan, 
(ii). The stated monthly income of borrowers and (iii) the annual 
percenatage rate borrowers.


## Key Insights for Presentation

For the presentation, I focused on just three key Insights
1. Top 10 Listing Category by loan count and percentage
2. The employment category that has the higest number of completed, 
defaulted and chargedoff loans.
3. The relationship that exist betweeen the number of friends that 
invested in a loan and number of investors that are not friends.
4. Income Status Impact on Loan Repayment Completion.


Afterwards, I examined the relationship that exist between home-owner 
status and loan amount with the respective monthly repayment amount.
I used a scatterplot to examine this relationship. I've madesure to 
use different color palettes for each quality variable to make sure 
it is clear that they're different between plots.