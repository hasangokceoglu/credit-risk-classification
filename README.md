# credit-risk-classification
Data Analytics and Visualisation Boot camp week 20 challenge

## Overview of the Analysis
### Purpose of the analysis: Create a model that is predicting the loan risk (0 - healthly loan and 1 - high-risk loan).
### Stages of the machine learning process:
#### Machine Learning Model 1 (Original Data):
**Question:** How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

**Answer:** The accuracy score of the Logistic Regression Model with Original Data is 0.95 (95%). In the classification report precision value of healty loans is 1(100%) (maximum) and 0.85 (85%) high-risk loans are correct. In Recall 0.99 (99%) of healthy loans are predicted correctly and high-risk loans prediction results is 0.91(91%).
#### Machine Learning Model 2: (Resampled Training Data):
**Question:** How well does the logistic regression model, fit with oversampled data, predict both the `0` (healthy loan) and `1` (high-risk loan) labels?

**Answer:** Oversampled data outcome is better than the Logistic Regression model with Original data.
Balanced Accuracy score increases from 0.952 to 0.993. 
The Logistic Regression Model with Oversampled Data accuracy score is 0.99 (99%). 
In Recall both healthy loans and high-risk loans predictions are 0.99 (99%).

### Summary
Based on analysis above, Model 2 is performing better than Model 1, as it has better accuracy score.
