# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis is to compare high risk loans to healthy loans based on information like loan size, interest rate, debt to income, and many other factors. 
The financial information the data was on included: loan size, interest rate, debt to income, and total debt among other factors.  We needed to predict the accuracy of healthy and high risk loans to determine the accuracy of each.
Some basic information about the variables we are trying to predict would include the number of healthy loans and number of high risk loans. There appear to be over 75000 healthy loans and 2500 high risk loans. This appears to show that this financial institution has done a good job of taking on high risk loans while having enough healthy loans to keep the company safe from the high risks. 
The stages of the machine learning process we went through as part of this analysis included splitting the data into training and testing sets using train_test_split after identifying the loan_status column. We then created a logistic regression model, confusion matrix, and classification report with the data.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Results for Healthy Loans:
    * Accuracy: .99
    * Precision: 1
    * Recall: .99
* Machine Learning Results for High Risk Loans: 
    * Accuracy: .99
    * Precision: .84
    * Recall: .95

The model correctly classified 99% of all loans, a very high accuracy. Of the loans labeled high-risk, 84% were correctly classified, indicating some false positives (healthy loans misclassified as high-risk). The model identified 95% of actual high-risk loans, meaning only 5% of high-risk loans were missed (false negatives).

## Summary

Summarize the results of the machine learning model, and include a recommendation on the model to use, if any. For example:

* The classification report seems to work best when providing information on the accuracy of predicting high risk loans vs healthy loans. The performance of this model does help predict loans with a high level of accuracy.

If you do not recommend any of the models, please justify your reasoning.
