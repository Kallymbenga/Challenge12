# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to pedict the risk of the healthy loans against risky loans
* Explain what financial information the data was on, and what you needed to predict.
We have many indicator like interest rate, borrower income, total debts etc..
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
classification report
* Describe the stages of the machine learning process you went through as part of this analysis.
logistic regression
model fit
model prediction
accuracy
and we did again with resample data
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
logistic_regression_model.fit(x_train, y_train) was used to fit the model using the training data
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
The precision for healthy loan goes well and for the high risk loan was much far under the value counts data gave us.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
The oversampled data predict the accuracy of 99% which is better than a prediction of the original data
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
 Machine Learning Model 2 gave us a better prediction with 99% of accuracy so it perfomed better tham the first model.
 
If you do not recommend any of the models, please justify your reasoning.
