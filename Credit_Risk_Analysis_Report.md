# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to use machine learning to determine how well we can predict if a person is healthy (low-risk) or unhealthy (high-risk) if they were to be given a loan. Essentially, we're predicting the creditworthiness of a potential borrower. The dataset used is of historical lending activity from a peer-to-peer lending services company. The variables I was trying to predict with these models were were how many loans were predicted to be low-risk and high-risk, vs how many are actually low-risk and high-risk. This data was displayed using a confusion matrix. I also wanted to predict how well we can determine if a person is low or high risk when being given a loan, using accuracy scores and recall.

## Results

* Machine Learning Model 1:
Reviewing the classification report above the logistic regression model does very well at predictig the '0' healthy loan and '1' high-risk loan lables with the classification report providing 99% accuracy. The recall states that from all positive cases (True Positive) 99.4%  were predicted correctly and the precision value of 99.3% (healthy) and 91% (high-risk) indicating from all positive cases that have been predicted as positive, the amount that are actually positive (ie low false positive).  In the confusion matrix we see there were 56 false positives, and 102 false negatives. Note that the dataset only had 3% high risk loans which would influence the results. 



* Machine Learning Model 2:
  * The challenge instructions did not ask for this to be completed. 

## Summary

The logistic regression model performs better at predictinng healthy loans than high-risk loans. Using more than one model type and comparing results may demonstrate better performance in predicting high-risk loans. The balance of the dataset and the machine learning models ability to predict high-risk loans is likley influenced with only 3% of the data being for this loan type. 
