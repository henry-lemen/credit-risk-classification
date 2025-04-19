# Module 20 Report

## Overview of the Analysis

The purpose of this analysis is to evaluate a model based on loan risk, determining how accurate the model is. This analysis was conducted based on data including the size of the loan, the interest rate, the income of the borrower, the borrowers debt to income ratio, the number of accounts the borrow has, derogatory marks such as late payments, their total debt, and the status of their loan. 

During the machine learning process, I split the data into testing and training datasets using the train_test_split fuction. Next, I created a logistic regression model from sklearn and then fit the model. After creating predictions,the final steps were to create the confusion matrix and classification report to review the results and analyze the accuracy score.

## Results

* Machine Learning Model Results:
    * The precision score of healthy loans is 1.00 and the precision score of high-risk loans is 0.84.
    * The recall score of healthy loans is 0.99 and the recall score of high-risk loans is 0.94.
    * The accuracy score of the model is 0.99.

## Summary

The healthy loan model performs better, as determined by the precision and recall scores being higher than that of the high-risk loans. However, it is more important to predict results of hihg-risk loans, which have a lower precision and recall score. Overall, the model has a high accuracy score of .99, meaning that it performs well to make predictions. 

Overall, I would recommend this model for company use. The precision and recall score are high for healthy loans, being 1.00 and 0.99 respectivelt. For High-risk loans, there is a precision score of 0.84 and a recall score of 0.94, both numbers are high as well. With an overall accuracy score of 0.99, this model will work well for the company.