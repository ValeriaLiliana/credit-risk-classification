# Module 12 Report Template

## Overview of the Analysis
Our objective is to assess lending data to determine the level of risk associated with a loan. The data under scrutiny encompasses variables such as Loan Size, Interest Rate, Income, Debt Ratio, and Total Debt. The primary focus is on predicting the Loan Status column based on this information.

To accomplish this, we commenced by importing and organizing the data, creating a set of X containing all columns except for Loan Status, and a set of y specifically for the Loan Status column. Utilizing the scikit-learn library, we divided the dataset into Training and Testing Data.

Subsequently, a Logistic Regression model was employed with a random state set to 1, and the model was fitted to the training data. Testing predictions were then generated using the testing dataset, yielding the outcomes presented below.



## Results

-Balanced Accuracy: 96.79%
-Accuracy: 99%
-Precision: 100% for non-high-risk; 84% for high-risk loans
-Recall: 99% for non-high-risk; 94% for high-risk loans

## Summary

The model exhibited an almost perfect identification rate for non-high-risk loans, approaching 100%. This key metric underscore the reliability and precision of the model, instilling confidence in its applicability.

