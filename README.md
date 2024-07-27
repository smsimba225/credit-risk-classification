# credit-risk-classification

Overview

The purpose of this analysis is to determine whether this logistic regression model can predict whether or not a loan is low or high risk. Factors considered in this analysis included data on the size of the loan, the interest rate, the borrower's income, the debt to incom ratio, the number of accounts the borrower held, derogatory marks against the borrower, and the total debt.  The data was split into training and testing sets.

Results

Logistic Regression Model:

Precision: 94% - the model had 100% precision in predicting low-risk loans, but it was only 87% precise in predicting high-risk loans.
Accuracy: 99% 
Recall: 97% - The model had 100% recall in predicting low-risk loans, but 95% recall in predicting high-risk loans.




Summary

The logistic regression model is doing a great job predicting the healthy loans (0 class) with 100% in both precision and recall. When it comes to predicting higher risk loans ( 1 class), the model predicts well, with 87% precision and 95% recall. this difference can be explained due to the significantly less amount of support test data. (625 vs. 18759). There is definitely room for improvement, perhaps with more training data, although this is a good start. The model itself has a 99% accuracy rating.

It is important to note from the confusion matrix that out of 19384, only 32 came up as a false negative. These indicate situations where the loan was actually high risk but the model predicted it to be low risk. This type of indication is a very low percentage, and indicates that the model would be a good tool to differentiate between high and low risk loans. The 86 false positives is a little higher percentage, but poses little risk to the bank, even if these customers were to be rejected for the loan.