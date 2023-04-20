# Credit Risk Classification

In this Challenge, I used various techniques to train and evaluate a model based on a loan risk. I will use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

I used the following steps to get the results:

* Split the data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Predict a Logistic Regression Model with Resampled Training Data

* Write a Credit Risk Analysis Report


# Results

# Model 1                                                     
Balanced Accuracy Score: 0.9520479254722232                  
                                                                                          
# Classification Report 

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384




# Model 2
Balanced Accuracy Score: 0.9936781215845847

# Classification Report

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384



# Summary

The model performs great and can predict the outcome of a healthy loan very well. However it struggles to give accurate results with high risk loans.


