 CreditWise Loan System

 Project Overview

CreditWise is a supervised machine learning project developed to predict whether a loan application should be approved or rejected based on applicant financial, personal, and credit-related information.

The goal is to assist banks and financial institutions in making faster and more accurate loan approval decisions.

 Problem Statement

Traditional loan approval processes rely heavily on manual verification of customer records and documents.

This process can lead to:

- Rejection of eligible customers
- Approval of high-risk customers
- Increased processing time
- Human bias in decision making

This project uses Machine Learning techniques to predict loan approval status automatically.

 Dataset Features

- Applicant Income
- Coapplicant Income
- Employment Status
- Age
- Marital Status
- Dependents
- Credit Score
- Existing Loans
- DTI Ratio
- Savings
- Collateral Value
- Loan Amount
- Loan Term
- Loan Purpose
- Property Area
- Education Level
- Gender
- Employer Category

Target Variable

- Loan_Approved
  - 1 = Approved
  - 0 = Rejected

Project Workflow

1. Data Cleaning
2. Missing Value Handling
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Label Encoding
6. One-Hot Encoding
7. Feature Scaling
8. Model Training
9. Model Evaluation

Models Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

Results

Model  Accuracy
Logistic Regression 88%
Naive Bayes 86% 
KNN 78.5%

Best Performing Models

- Logistic Regression achieved the highest overall accuracy (88%).
- Naive Bayes achieved the highest precision (81.1%), making it more suitable when minimizing false approvals is important.

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Author

Rahul Bisht
