# Prosper Loan Data Exploration
## by Jimmy Le


## Dataset

There are 113,937 loans in the dataset with 81 features.  Most variables are numeric and categorical in nature.

The dataset features can be split into two main categories:

1. Borrower information
2. Loan performance information


## Summary of Findings

In this notebook, I wanted to find out which features were the best indicators for predicting the highest rate of return.

In the univariate exploration, I visualized and addressed minor quality and tidiness issues for the following features:

### Numerical Features
1. Estimated Returns
2. Actual Returns
3. Debt to Income Ratio

### Categorical Features
1. Income Range
2. Credit Grade

The Actual Returns for the dataset was engineered from a simplified version of Prosper's Net Annualized formula.

The bivariate exploration revealed the numerical categories did not have any obvious correlations.  When comparing the estimated returns with the income range and credit grade,
it became apparent that the credit grade is a much better predictor for returns than the income range.  The credit grade spanned every income range, however I noticed that
borrowers with higher incomes often received better credit ratings.

The multivariate exploration revealed again that the credit rating was the best primary predictor for estimated returns.  When introducing the loan status, loans that have
been completed or are current followed a linear correlation between estimated and actual returns.

## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.
