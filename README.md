# credit-risk-classification
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis
The purpose of the analysis was to utilize the Logistic Regression model with two different datasets (original and oversampled) to make accurate predictions on healthy and high-risk loans. Specifically, we were trying to predict loan status. We were to use a dataset with variables such as an_size, interest_rate, borrower_income, debt_to_income ratio, number_of_accounts, derotatory_marks, total_debt and loan_status. The total number of loans in the original dataset was 77,536. The loans were categorized into two classes: healthy (75,036) and high-risk (2,500). The classes are defined as 0 for healthy and 1 for at-risk. 

### Stages
1. Prepare data
2. Separate data (labels)
3. Split data into training and testing datasets
4. Use Logistic Regression model
5. Make prediction with testing data
6. Evaluate performance with classification report

## Results
* Machine Learning Model 1:
  * Accuracy: 0.9520479254722232
  * Precision: 0 class = 1.00 / 1 class = 0.85
  * Recall: 0 class = 0.99 / 1 class = 0.91



* Machine Learning Model 2:
  * Accuracy: 0.9936781215845847
  * Precision: 0 class = 1.00 / 1 class = 0.85
  * Recall: 0 class = 0.99 / 1 class = 0.99


## Summary
Using the original dataset, the logistic regression model faired very well in terms of the 0 class. As seen above, the precision was 1.00 and the recall was 0.99, which are positive factors. However, the model did not do as well for the 1 class. Where the 0 class had strong results, the 1 class had precision at 0.85 and recall at 0.91. Overall, the 1 class did not do terriblly, but not as good as the 0 class.

After using the oversampled dataset, we discovered that for the 0 class, the results were same for the original and oversampled data. The same can not be said for the 1 class. The 1 class seems to have very similar precision with the original and oversampled data, but has a difference when it comes to recall. The recall with the oversampled data is actually higher than the recall from the original data. With the oversampled data, we could come to the conclusion that we are able to make a more accurate prediction than with the original data.
