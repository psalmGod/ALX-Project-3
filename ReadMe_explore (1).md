# Loan Data from Prosper Exploration¶


## Data Set
This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.


## Summary of Findings

In the process of exploring this data set, I centered my focus on loan status and borrowers rate, trying to uncover necessary features needed to determine these two variables, I made use of the employment status of borrowers , stated monthly income and the prosper risk score attached to each loan, and I discovered some beautiful relationships, first I saw the existence of a strong negative relationship between prosper risk score and borrowers rate and also, I discovered that most charged off loans and past due loans were initially highly risky loans on an average count using the prosper risk score scale. furthermore I discovered some interesting patterns after plotting some multivariate graphs, I observed that at all levels of risky scale and borrowers rate unemployed and retired individuals tend to surpass the employed individuals in loan aquisition,also I discovered that for current, completed and charged off loans the risk score for unemployed individuals loans always lag behind against all employed individuals which is an indicator that the most risky current, completed and charged off loans are collected by unemployed individuals ,while the most risky past due loans were collected by employed individuals as the risk score for employed individuals turns out to be the smallest. lastly, I observed that at high borrowers rate we have quite low prosper score within a stable monthly income, which is an indicator of risky loans for almost all income levels at high borrowers rate.


## Key Insights for Presentation


For the presentation, I focused on the Prosper risk score and employment status effect on borrower’s rate and Loan status leaving out the stated monthly income effect as not much relation was seen in the exploration phase. I started off by introducing the distribution of Borrowers rate and Prosper Risk score, the I went on to show the relation between the above variables using the boxplot and point plot, then I showed the relationship between prosper risk score and Loan status using boxplot, after which I showed the multivariate relation as regards employment status effect on the two established relationships above respectively, using bar plots.



```python

```
