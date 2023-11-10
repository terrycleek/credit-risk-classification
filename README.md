# credit-risk-classification
Module 20 Challenge

--
## Overview of the Analysis

*The purpose of this analysis was to build a machine learning model to a loan status based on financial information. Essentialy to determine whether a loan was Healthy(0) or High risk(1)
* We wanted to predict Loan Status, our target variable which would be 0 or 1. Some of the finanical information the data was based on was; Loan size, interest rate, borrower income, debt to income, number of accounts, derogatory marks, and total debt.
* Some of the variables I was trying to predict such as value counts represnt the number of healthy loans or high risk loans. or isntances there of. Precision, recall and f1-score which represnet how well the model correctly predicts a behavior, correctly identifies a behavior, and the balanced measure between both the precision and recall. 
* The stages of the machine learning process I went through as part of this analysis was the Data loading and preparation using a starter file or juopyternotebook template. Importing the necessary dependencies to load the lending_data.csv file and the machine learning modules used. Some minor data preprocessing. Setting the data into labels y "loan_status" and features X, "the reamaining data columns". Split the data into train and test for the machine learning model. Create a logistic Regrssion model using machine learning and the "train data". Module evaluation by calculating the accuracy score and classification report. 
* I used LogisticREsgression and RandomOverSampler for resampling the data to get more accurate results. 

--
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy 0.95. Relatively good accuracy which represents a good balance between correctly classifying healthy loans and high risk loands in both cases 
  * Precision for class "0" healthy loans = 1.0  shows that this module is extremely good at predicting healthy loans. 1 is the best possible score, for "1" unhealthy a 0.85 value is still good but much lower than 1. could be improved for predicting unhealthy loans
  * Recall scores of 0.99  for healthy and 0.91 shows that this model is pretty good at correctly identify healthy loans 99% of the time and 91% for unhealthy loans. Once again some imporvment might be good for unhealthy loans.



* Machine Learning Model 2:
  * Description of Model 2 Accuracy is now 99% which shows the overall correctness and balance between both vraibles. A substantial increase over the previous model. 
  * the Precision stayed the same for "0' healthy loans at 1. which mean it still is able to correctly predict healthy loans close to all of the time. However precision took a small hit with "1" high risk loans dropping to 84. which is saying this model can correctly predict rouhgly 84% of the time. not too big of a difference.
  * The Recall scores stayed the same for "0" healthy loans which says it correctly identifiys 99% of the time for healthy loans. Also for "1" high risk loans the model jumped it up to 99% also a substanital increase from the previous model. 

--
## Summary


* Both Models perform well in terms of accuracy precision and recall for both classes 0 and 1. Module 2 which uses resampled data shows an improved performance in correctly identifying high risk loans and also higher recall. 
* performance does depend on the problem we are trying to solve. If you are trying to accurately indentify high risk loans that might be the major priority regardless of whatever else takes a hit. I am not really sure what the other goal is in besides testing out machine learning but the decision does indeed depend onf what specific goals and priorities one is looking for. 

From my basic understanding I would strongly recommend in this scenario to use the second Module.
