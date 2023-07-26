# credit-risk-classification
credit-risk-classification

## Overview of the Analysis
The purpose of the analysis is to evaluate loan risk and the credit worthiness of the borrower. The financial information data used for the model was loan size, interest rate, potential boorower income, debt to income reation, number of borrower accounts, and the number of derogatory marks for each potential borrower. The variables we are trying to predict with the model were high risk loans and low risk loans. A logistic regression model was used to show the relation between the factors of the data and the results. This was then used to predict approvals and rejections. A random over sampler was used to resample the data. The logistic regression model was then run again.

## Results
* Machine Learning Model 1:
* High Risk Loan
  * Accuracy: 99%
  * Precision: 85%
  * Recall Scores: 91%

* Low Risk Loan
  * Accuracy: 99%
  * Precision: 100%
  * Recall Scores: 99%


* Machine Learning Model 2:
  * High Risk Loan
  * Accuracy: 99%
  * Precision: 84%
  * Recall Scores: 99%

* Low Risk Loan
  * Accuracy: 99%
  * Precision: 100%
  * Recall Scores: 99%

## Summary
Model 1 and model 2 predicted the same percentages for accuracy, precision, and recall scores. Model 2 had a higher recall score for high risk loans while model 1 had a higher precision  score by one percentage point. Given that the recall score for the high risk loan is much higher in model 2, I would say that model number 2 seems to perform better. I would say that it is more important to predict the high risk lows since those are the borrowers that are deemed unlikely to repay the loan and more likely to default on the loan.
