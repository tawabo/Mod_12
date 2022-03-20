# Mod_12


# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this Challenge, you’ll use various techniques to train and evaluate models with imbalanced classes. 




* Explain what financial information the data was on, and what you needed to predict.
You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.




* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
value_counts
balanced_accuracy_score

* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

train_test_split
LogisticRegression
balanced_accuracy_score
classification_report

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.




* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
     precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

 its predicting low risk very well however 15 percent difference is unacceptable to most people



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384
same as above the healthy loans are great however with a slight better prediction of high risk loans only 16 percent most analysts would not accept this model

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Model 1 has a bit more realistice avg's so would go with Model 1 between the two models
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
* No 

If you do not recommend any of the models, please justify your reasoning.
I would not recommend either model as the data consists of to many Low risk credit that high risk does not show as much
