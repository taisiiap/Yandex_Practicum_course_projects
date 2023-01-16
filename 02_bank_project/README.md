# Bank Project

## Task:
To check the data and hypotesis:
   1. married people with children repay the loan in time
   2. A larger number of children also increases the chance of returning the loan
   3. People with high incomes do not have problems with debts
   4. The purposes of the credit have a significant influence on the repayment of the credit
   
## Description:
Credit scoring is widely used by banks in order to quickly decide whether to approve or deny a loan. Based on the data, we will compare the reliability of people with different backgrounds and identify patterns

## Results
There were anomalies in the table, such as missing values, explicit and implicit duplicates, typos, fractional numbers. All this had to be corrected and prepared for further work.

All customers were categorized by several groups united by a common feature. People with a similar income level, goals of the loan were united.

First and second hypotheses that married people with children (the more the better) repay the loan on time was confirmed partially. The presence of children affects the repayment of the loan negatively, customers without children take loans and pay them back much more often than customers with children. However, among the clients with 5 children (the smallest group) there was not a single delay. But, their sample is small, so we can't rely on it very much. Married couples has a good effect on the repayment of the loan, however, the most responsible borrowers are widows or widowers.

The 3rd hypothesis has not been confirmed, there is no direct relationship between the level of income and the repayment of the loan. The borrowers with an average income of 30001-50000 are the most responsible. Even people with very high incomes have a worse delinquency rate.

Loans for a wedding or real estate transactions have a higher percentage of repayment than loans for car transactions and education, which confirms the 4th hypothesis that the purpose of the loan also matters in the ideal borrower's account.

When building a credit scoring model , the bank 's credit department needs to rely on the following people:

 - borrowers without children
 - widows, widows, people in a marriage or relationship
 - income is mandatory, but the size does not affect
 - borrowers who take out a loan for a wedding or real estate transactions.

## Company profile:
Bank, Credits 

## Stack:
Python, Pandas

## tags:
data analisys, Python, Pandas, finance analysis
