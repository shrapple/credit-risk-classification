## Overview of the Analysis

Looking to predict healthy vs high-risk loans by looking at previously
collected instance's loan data (loan amount, interest rate, derogatory marks) & borrower information (income, debt to income ratio, number of accounts, & total debt). Each categorized as healthy (0) or high risk (1).
Using a Logistic Regression Model, the collected measures are then used to predict whether future loans in similar instances will be high-risk or healthy.


## Results

It's important to note that the data was imbalanced. Out of 77,536 instances; 75,036 were healthy and 2,500 were high-risk

* Model Accuracy: 
  * The model scored 99% accuracy and 95% balanced accuracy
* Model Precision:
  * The model was least precise when predicting high risk loans at 85%
  * Healthy loans scored a shocking 100%. This could be due to the imbalance.
* Model Recall:
  * Healthy loan recall was 99%
  * High-risk loan recall was 91% 


## Summary

Overall, this machine learning model performed really well. 

The number of predicted healthy but categorized as high-risk loans is **nearly half** the number of actual healthy loans predicted to be high-risk.

The number of missed high-risk loans was **a tenth** of the predicted high-risk loans that were actually healthy loans.

I recommend this model as a tool with the understanding that the high-risk data isn't necessarily as represented as it needs to be to be able to accurately categorize them as so.
