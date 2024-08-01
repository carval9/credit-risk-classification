# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

## Overview of the Analysis
The purpose of the analysis is to build a model a model that can identify the creditworthiness of borrowers.

The data we have is loan size, interest_rate, borrower income, debt income,number of account, derogatory marks, total debt y loan status. What we use to predict was loan status.

For this Module I used LogisticRegression method, for this we separate the data in test and train, then we initiate the logistic regression and fit the model. Once this is done I was able to predict.

## Results
Below you'll find the Accuracy, Precision and Recall scores for both cases:

0
Accuracy: 1
Precision: 1
Recall: 0.99

1
Accuracy: 0.89
Precision: 0.85
Recall: 0.92

## Summary
I would recommend the use of the model, letting the company know that it is not perfect, which means that there will be some mistakes, but as seen in the scores shown classification report the overall score is high.