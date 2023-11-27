# Loan-Repayment-Prediction-Using-Deep-Learning

## Overview

This project leverages deep learning techniques to predict loan repayment, specifically determining if a customer will repay the loan. The dataset used is sourced from the Lending Club and encompasses borrower information and loan details. The deep learning model is trained to make predictions based on various features.

## Datasets

The project relies on two datasets:
- lending_club_info.csv:** Information about each column in the lending_club_loan_two dataset.
- lending_club_loan_two.csv:** The primary dataset containing borrower and loan details.

## Usage
- Open and run the loan_repayment_prediction.ipynb notebook in the notebooks directory.
- Make sure that the datasets and the python code are in the same directory
- Follow the step-by-step instructions in the notebook to explore the dataset, preprocess the data, and train the deep learning model.
- Evaluate the model on cross-validated data and unseen test data.

## Results

-**The deep learning model achieved acceptable results in predicting loan repayment with f1-score of 94% for positive cases and 61% for negative cases. Details of the model's performance can be found in the notebook.

#For sure this result can be improved by the future works of

-More feature engineering
-Different architecture for DL model
-Investigation of the role of threshod 0.5 and adjust it to the optimal value by looking to AUC and ROC.
-Tune the hyper parasmeter of learning rate (alpha) and etc. using grid search
-and so on.
