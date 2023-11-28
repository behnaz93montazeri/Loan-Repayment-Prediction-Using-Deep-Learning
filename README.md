# Loan-Repayment-Prediction-Using-Deep-Learning

## Overview

This project leverages deep learning techniques to predict loan repayment, specifically determining if a customer will repay the loan. The dataset used is sourced from the Lending Club and encompasses borrower information and loan details. The deep learning model is trained to make predictions based on various features.

## Datasets

The project relies on two datasets:
- lending_club_info.csv:** Information about each column in the lending_club_loan_two dataset.
- lending_club_loan_two.csv:** The primary dataset containing borrower and loan details.

The primary dataset, `lending_club_loan_two.csv`, is large, and GitHub has file size limitations. Therefore, the dataset has been split into two parts. To access the full dataset, follow the instructions below.

### Instructions for Accessing the Full Dataset

1. **Download the Split Parts:**
   - Download `dataset.partaa` and `dataset.partab`

2. **Combine Split Files:**
   - For Unix-based Systems (Linux, macOS):
     ```bash
     cat dataset.part* > lending_club_loan_two.zip
     ```
   - For Windows:
     ```bash
     copy /b dataset.part* lending_club_loan_two.zip
     ```

3. **Extract the Combined File:**
   - Extract the combined zip file to obtain `lending_club_loan_two.csv`.

4. **Place the Datasets:**
   - Place `lending_club_loan_two.csv` next to `lending_club_info.csv` in the project directory.


## Usage
- Open and run the loan_repayment_prediction.ipynb notebook in the notebooks directory.
- Make sure that the datasets and the python code are in the same directory
- Follow the step-by-step instructions in the notebook to explore the dataset, preprocess the data, and train the deep learning model.
- Evaluate the model on cross-validated data and unseen test data.

## Results

-The deep learning model achieved acceptable results in predicting loan repayment with f1-score of 94% for positive cases and 61% for negative cases. Details of the model's performance can be found in the notebook.

<img width="600" alt="Screenshot 2023-11-27 at 6 13 24 PM" src="https://github.com/behnaz93montazeri/Loan-Repayment-Prediction-Using-Deep-Learning/assets/124638983/aef84c2a-bd1e-48ef-aa9c-36f517986985">


## Future Work

The following areas have been identified for potential improvement:

1. **More Feature Engineering**
2. **Different architecture for DL model**
3. **Investigation of the role of threshod 0.5 and adjust it to the optimal value by looking to AUC and ROC**
4. **Tune the hyper parasmeter of learning rate (alpha) and etc. using grid search**
5. **And so on**
