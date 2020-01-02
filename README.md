
# Installations:
- Python 3 
- Anaconda 
- Numpy
- Pandas
- Matplotlib
- Seaborn

# Project Overview


## Business Understanding

This project is on a data set from Prosper, which is America’s first marketplace lending platform, with over $7 billion in funded loans. Since the dataset talks about the loan entries, it is important to get some business understanding in terms of some key business questions. 

Which are the major income buckets of our existing customers?
Knowing the major income buckets is relevant in understanding the current loan distribution patterns that prevails for customers. This would help in knowing which type of income customers are most likely to take loans.

How are ratings distributed across the population and does it affect the loan to be given?
Rating distribution pattern adds to the business understaing relevance by shedding light on the part if more loan is given to the customers having higher risk of returning.

How is loan amount distributed across Occupation?
This question let us understand which type of customers are more into taking the loan.

How does loan amount differ with respect to the income range?
The idea behind getting the answer towards this question is that it will help us understand if the higher amount of loan is being given to a customer of lower income range.

How Borrower Rate has changed over years for Homeowners vs Non-Homeowners?
This one part of analysis would build business understanding towards how the rate prevails if a person has his own home or not.

## Project Objective

The primary objective of this project is to analyse the different variables that can impact the loan status. Also, to get some quantifiable insights by performing univariate, bivariate and multivariate analysis that could describe relationships among multiple variables using statistics and data visualizations.

Varied plots like bar plot, box plot, line chart etc have been used depending on the type of variable to be analysed in the exploratory data analysis.

## Data Understanding

This data set contains data for 113,937 loans with 81 variables corresponding to each loan entry. For the purpose of analysis, some variables namely 'ListingNumber', 'ListingCreationDate', 'IsBorrowerHomeowner','Term', 'LoanStatus', 'ClosedDate', 'BorrowerAPR', 'BorrowerRate','ProsperRating (Alpha)','BorrowerState','Occupation','DebtToIncomeRatio', 'IncomeRange','LoanOriginalAmount','LoanOriginationDate', 'LoanOriginationQuarter','Investors' have been taken into consideration.

Some of the findings were-
1. Avg. original loan amount across the population was $8337.01385 with a SD of 6245.80058.
2. Avg.stated monthly income was $5.608026e+03.
3. Public records in last 10 years has been 113240.
4. Most entries for ocuupation variable comes under "others" which may highlight that customers were not intersted in revealing their occuptaion.

## Data Preparation

Since, this exercise was to explore various variables and see their impact on loan amount, no data prepartaion like handling categorical variables etc, has been performed. 

## Missing Value Handling
Since, this exercise was to explore various variables and see their impact on loan amount, few variables which had missing values were ignored from the analysis. However, if the process needs to go further for modelling, missing values either need to be imputed or deleted as per the variable.

