# Module 20 Report

## Overview of the Analysis

The dataset given for this exercise contained lending data that captured various metrics on loans risk from a peer-to-peer lending company. This dataset contained information on whether or not the loan was high-risk in the 'loan_status' field. Our goal was to use the other data given to train a model to predict loan_status in order to find out whether a loan was high-risk (loan_status = 1) or healthy (loan_status = 0). 

The process began with splitting the data into training and test sets so that we could properly train and evaluate the model. Logistic regression was used as the method for analysis because the analysis required binary classification of a loan as 'healthy' or 'high-risk'. Using the logistic regression model the data was fit and used to predict loan_statuses. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model:
    * Loan_status = healthy:
        * Precision: 1.00
        * Recall: 1.00
        * Accuracy: 0.99
    * Loan_status = high-risk:
        * Precision: 0.87
        * Recall: 0.89 
        * Accuracy: 0.99

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

The logisitic regression model used to predict loan status worked extremely well when it came to predicting healthy loans as it did so with 100% precision. When it came to high-risk loans the precision was only 87%. 

Precision is the ratio of true positives to true positives plus false positives. 

This means that the model gave some false positives for a high-risk loan. From the perspective of the lending company it is better that this is the outcome as it would be more beneficial to omit some people who are worthy of a loan rather than give people a loan who will default. The precision for the healthy loans is 100%, meaning there were no false positives. 

For this reason, I would recommend the model to the lending company because it will not give someone a loan who will default. 

