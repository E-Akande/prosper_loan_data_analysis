# (Prosper Data Exploration)
## by (Akande Emmanuel)


## Dataset

> This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower/ interest rate, current loan status, borrower income and many others.

> The sole purpose of this project is to ascertain borrowers intent/ loan outcomes and communicate data findings using 10 - 15 of the variables.

> To achieve this, I performed preliminary wrangling like: sorting missing value issues under ProsperRating (Alpha) and TotalProsperLoans plus fixing data type issues with LoanOriginationDate & StatedMonthlyIncome. 


## Summary of Findings
> In the exploration, I found that the most prevalent LoanStatus was current loans. 
Most completed payments were by employed and self employed borrowers.
C and AA were the most common and least prevalent Prosper Ratings of borrowers respectively. 
Again, D was the most common Prosper rating amongst both borrowers that defaulted and those that Completed payments too.
However, AA turned out the ProsperRating (Alpha) with the highest Completed to Defaulted ratio of all employed borrowers.
Evidently, the relationship between Prosper ratings and Completed Payments is absolutely linear.
The higher the prosper ratings, the higher the completed to defaulted ratio. 

> Again, Employment Status, Loan Status, Stated Monthly Income were considered in assigning ProsperRating (Alpha) and its quite a surprise that individuals that took the highest loan amounts tended to complete payments better than others that took less. At same time, the number 1 reason for taking loans was debt Consolidation. Plus, borrowers that Listed Debt Consolidation or Business as reasons for taking loan had more completed loans than all other categories of Listings. They also had the largest size of Defaulted Loans alongside Listing HomeImprovement.

> Not surprisingly though, employed or self-employed borrowers with monthly income greater than average StatedMonthlyIncome tend to be associated with more Completed payments.

## Key Insights for Presentation

> For the presentation, I chose to focus the relationship between LoanStatus, ProsperRating (Alpha) and EmploymentStatus.

> I begin with introducing the LoanStatus and ProsperRating (Alpha) variables. I then follow up with the transformed LoanStatus and ProsperRating (Alpha) count plot. 

> I then move on to introducing EmploymentStatus and showing the relationship between the LoanStatus and EmploymentStatus too.

> Next, I show the ProsperRating (Alpha) and EmploymentStatus relationship using the catplot and finally, I show the relatiosnhip between LoanStatus, ProsperRating (Alpha) and EmploymentStatus using both catplots under it. 