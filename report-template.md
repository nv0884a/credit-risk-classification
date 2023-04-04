# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
- [[18663   102]
 [   56   563]]
0.9520479254722232

- The accuracy score was about 95% so it was fairly accurate.
- Used train_test_split for the initial x-train and y-train
- It proved to be effective enough at predicting the loan status outcome compared with the rest of the data


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
 [[55964   307]
 [  286 55985]]
0.9947308560359689

-The accuracy score was over 99% for the resampled data
- Much more effective than the first dataset
- Due to the use of RandomOverSampler the x_resample and y_resample outputs were more effective at predicting loan status

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

I would recommed the second dataset test, as shown it is much more effective at predicting outcome. If this was done with unsupervised learning, I'm not sure one would have gottent the same results with such accuracy.


If you do not recommend any of the models, please justify your reasoning.
