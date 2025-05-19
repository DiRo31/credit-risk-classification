# credit-risk-classification
Module 20 Challenge


Hello!

This challenge was based on: https://bootcampspot.instructure.com/courses/6909/assignments/92711 The data used can be found in the link and in the Resource folder. 

If there are any questions, please reach out!


# Credit Risk Analysis Report

## Overview of the Analysis

The purpose of this analysis was to evaluate the performance of a logistic regression model in predicting credit risk for loans. The model was trained to classify loans as either healthy (0) or high-risk (1) based on various financial features. 

## Results

The logistic regression model's performance can be summarized as follows:

* Accuracy: 0.99 (99% of predictions were correct)
* Healthy Loans (0):
  - Precision: 1.00 (100% of predicted healthy loans were actually healthy)
  - Recall: 0.99 (99% of actual healthy loans were correctly identified)
* High-Risk Loans (1):
  - Precision: 0.85 (85% of predicted high-risk loans were actually high-risk)
  - Recall: 0.91 (91% of actual high-risk loans were correctly identified)

## Summary

The logistic regression model was effective in predicting credit risk. With an accuracy of 99%, it correctly classifies most of loans. This model was particularly adept in identifying healthy loans, meaning it rarely misclassified healthy loans. This in important toward accurately identifying opportunities. 

For high-risk loans, the model's performance was also strong, though slightly less so than for healthy loans. With a precision of 85% and recall of 91% for high-risk loans, the model was effective for identifying potential risks, but there is some room for improvement. Given these results, this model is better suited for credit risk assessment for initial risk measurement. 

To  improve the model, the company could consider:
   - Collecting more data, especially on high-risk loans
   - Testing other machine learning algorithms to see if they perform better

In conclusion, this logistic regression model provides a strong foundation for credit risk assessment and can be used as part of the company's loan evaluation process.
