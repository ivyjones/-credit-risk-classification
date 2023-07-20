### Loan Status Prediction Analysis

## Overview of the Analysis
The purpose of this analysis is to build a machine learning model that predicts loan status based on various features such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The goal is to determine whether a loan is high-risk or healthy based on these features. We will evaluate the performance of the model using accuracy, precision, and recall scores.

## Results
Using a Logistic Regression model, we obtained the following evaluation metrics:
- Accuracy Score: 99%
- Precision Score:
- Healthy Loans (Class 0): 100%
- High-Risk Loans (Class 1): 84%
- Recall Score:
- Healthy Loans (Class 0): 99%
- High-Risk Loans (Class 1): 91%

## Summary
The logistic regression model achieved excellent performance with an accuracy of 99%. It accurately predicts healthy loans with a precision of 100%. However, it has a lower precision of 84% for high-risk loans. Additionally, the recall score for high-risk loans is 91%, indicating that it is capable of identifying most high-risk loans but may still miss some.

We have explored two approaches in this analysis: one with the original data and the other with resampled training data using the RandomOverSampler technique to address imbalance. The model with resampled data showed an improvement in predicting high-risk loans with a recall score of 99%. This indicates that the model using oversampled data is slightly better at identifying high-risk loans compared to the original model.
