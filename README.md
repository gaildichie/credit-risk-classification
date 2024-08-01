

## Overview of Analysis
This is an analysis of dataset of historical lending activity from a peer-to-peer lending services company. built a model that can identify the creditworthiness of borrowers.

The data was based on loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt and loan status 
and the prediction was based on the loan status.
The variable is an int64.
The analysis started with importing dependencies, importing the lending data, and separating the 'loan status' (y) column from the features(X).
Data was split into test, train models using the train-test-split, with a random state of 1.
Next, data was instantiated with the Logistic Regression model with a sg solver and random state of 1.
Next, data was fitted with the train variables and predicted with the test variables.
Lastly, the Confusion Matrix showed the number of correct and incorrect predictions for each class and the
Classification Report provided precision, recall, F1 score, and support for each class, helping to understand the model's performance.


##Results

The Logistic Regression Mode used predicted and classifed the following the scores:
      * Accuracy score of 0.99
      * Precision score for healthy loan = 1, high-risk loan = 0.85
      *Recall scores for healthy loans = 0.99, high -risk loan = 0.91
         
