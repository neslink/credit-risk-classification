# credit-risk-classification
Module 20 Challange

# Overview - 
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Purpose -

Our primary objetive is to build a Machine Learning model that is capable of predicting the risks involved in loans. To view the risks involved between healthy and high risk loans.

# Data frame -

The data frame we used contains financial information that is related to loan applications. The type of information are loan sizes, debt to income, borrower income, number of accounts and total debt. Healthy loans are classified as (0), while high risk loans are (1).

# Accuracy -

Accuracy is measured by the overall correctness of the prediction given by the model. 

"Precision: Precision measures the accuracy of positive predictions. Recall: Recall, also known as sensitivity, measures the proportion of actual positives that were correctly identified by the model."

- Accuracy of the model with original data was 95%.
- Recall for '0' (Healthy loan) applicants is 99%, while the recall for '1' (High-Risk loan) applicants is only 91%.
- However, the accuracy of the model, fit with oversampled data has increased to 99% balanced accuracy score.
- Also the recall for '1' (High-Risk loan) applicants has increased from 91% to 99%.

## Analysis -

Our machine learningh model has now a accuracy score of 99%.
So now after using our model the recall for both '0' (healthy loan) and '1' (High-Risk loan) applicants is 99%, which makes our model more robust & accurate than the previous one.
With this model the company can identify the creditworthiness of borrowers and categorise them into healthy or risky loan applicants with 99% accuracy.