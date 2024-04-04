# credit-risk-classification

## Overview of the Analysis

  In this analysis, we use historical data from a peer-to-peer lending services company to build a model that would allow us to predict and determine the creditworthiness of potential borrowers. Essentially, we are examining past lending data and using it to predict the loan status of future borrowers. The data set provided information on loan size, interest rates, borrower income, debt-to-income ratio, and other finacial information from previous loans. The label that we looked at was loan status and the variables were the loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, drogratory marks and total debt. Overall, we were trying to predict the loan status. 
  The steps we took to build and apply this model are as follows. First, we seperated the columns into the labels and the features. Then, we seperated the rows into training data sets and test data sets with train_test_split. Then, we fit a logistic regression model with the x_train and y_train values. Then, we ran the logistic regression model with the x_test values to generate testing_predictions. We evaluated the model's performance by generating a confusion matrix and a classification report. The confusion matrix was used to visualize the accuracy of the classification model by showing the number of true positives, true negatives, false positives, and false negaties. The classification report gave us values for the precision and recall of the model, which allowed us to better assess the strength of the model. 

## Results
- Precision: The precision for the model is 0.92
- Accuracy: The accuracy for the model is 0.99
- Recall: The recall for the model is 0.95

## Summary

Overall, this model seems to do a good job of predicting future creditworthiness of potential borrowers by predicting the loan status. It has high precision and recall values (>90%) and the accuracy value is high enough that it accurately models the data set without merely describing the training values. Based on its high performance values in the classification report, I would recommend that the company implement the model. 

**Resources**
I referenced class materials to recall the coding syntax for the model building.
