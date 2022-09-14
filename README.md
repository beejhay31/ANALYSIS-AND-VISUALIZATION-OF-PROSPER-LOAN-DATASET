# ANALYSIS-AND-VISUALIZATION-OF-PROSPER-LOAN-DATASET

# (Prosper Loan Data Exploration)
## by Adegoke Toluwani


## Dataset

This data set contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others. See this data dictionary to understand the dataset's variables. The data set consists of 81 features (rows) of 113937 customers of a bank. Of all the 81 features, 50 features are float data types, 17 are objects/categorical, 11 are integers, 3 are boolean features. 


## Summary of Findings
In the exploration, I found that there was a strong relationship between the borrower rate of a borrower and his/her upper and lower credit score score range. The relationship between credit score ranges and borrower rate was found to be an approximately linear one. For the Loan Amount, after initially plotting with a standard scale, I couldn't clearly see the relationship it had with prosper score and Monthly income but after a log-scaling, the plotting became clearer as I was able to discover the positive correlation with both monthly income and prosper score. Not to put away the fact that Income range also shared a positive relationship with loan amount.
Outside of the main variables of interest, I couldn't really find any peculiar relationship between the other variables considered except how the income range's distribution across loan amount was the same and didn't change across all loan status.
It was also quite amazing to discover that once loan is past its due repayment day, retired employees are more affected with an high borrower rate.


## Key Insights for Presentation
For the presentation, I focused on some chosen numerical features ('DebtToIncomeRatio', 'TotalProsperLoans', 'TotalProsperPaymentsBilled', 'CurrentDelinquencies', 'EmploymentStatusDuration', 'CreditScoreRangeUpper', 'CreditScoreRangeLower', 'ProsperScore', 'StatedMonthlyIncome', 'BorrowerRate', 'LoanOriginalAmount') and categorical features (LoanStatus, EmploymentStatus, IncomeRange). I started by introducing the
borrow rate and the loan amount variables, followed by the correlation plot betweeen the numerical variables then. Afterwards, I visualized Borrow Rate by Credit Score Range Upper by Credit Score Range Lower, then got a clearer view into the relationship between Loan amount, Monthly income and Prosper score. I also introduced two other plots which showed how the categorical feature (Loan Status) interacted with two of the features of interest (Borrow Rate and Loan Amount) and some other features. I've made use of different color palettes for each quality variable and different encoding practices to differentiate these variables between plots.
