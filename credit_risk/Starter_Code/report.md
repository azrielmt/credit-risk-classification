# Module 20 Report

## Overview of the Analysis

In this module, techniques related to Machine learning were used to train models based on loans and its risks. This dataset is based on the historical lending activity from a company. We wanted to find out how accurate these loans were and if they were worthy enough, which differentiated between healthy and high-risk loans.

Based from the dataset, the data is based on:
- Loan size
- Interest rate
- Borrower income
- The debt to income
- Number of accounts
- Any deragatory marks
- The total debt
- Loan status (later dropped)

We would first get the target variable, which would be the loan status, and then separated the data into training and test data.  We would try modelling with the original data and then the resampled training data. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  - Accuracy: 0.9520479254722232
  - Precision: 100% and 85%
  - Recall: 99% and 91%

* Machine Learning Model 2:
  - Accuracy: 0.9936781215845847
  - Precision: 100% and 84%
  - Recall: 99% and 99%

## Summary

It seems as though the healthy loans are well enough. The fact that it has a precision of 100% means it works. High-risk only has an 85% precision rate, but mind the low number as there are only 619 high-risk loans. I don't think that would be something to use in regards to making decisions. I think Model 2 might be the best model to go with due to the fact that there are more data points used, although the precision percentage may raise questions. 