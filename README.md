# Loan Default Prediction Model

This Jupyter Notebook presents the development and evaluation of a logistic regression model designed to predict the probability of loan default based on borrower characteristics. The model uses a dataset with details such as credit lines outstanding, loan amount, income, FICO score, and employment history to estimate the risk of default.

## Dataset Overview

The dataset includes various features related to borrowers, such as:
- `customer_id`: Unique identifier for the customer.
- `credit_lines_outstanding`: Number of credit lines the borrower has.
- `loan_amt_outstanding`: Current loan amount outstanding.
- `total_debt_outstanding`: Total debt including the current loan.
- `income`: Borrower's annual income.
- `years_employed`: Number of years the borrower has been employed.
- `fico_score`: FICO score of the borrower.
- `default`: Indicator if the borrower has defaulted (1) or not (0).

Additional computed features for analysis:
- `debt_to_income`: Ratio of total debt to annual income.
- `payment_to_income`: Ratio of loan payment to annual income.

## Model Development

The model development process includes:
1. Data preprocessing and feature engineering.
2. Exploratory data analysis to understand feature distributions and relationships.
3. Logistic regression model training and validation.
4. Performance evaluation using metrics such as accuracy, ROC-AUC, precision, recall, and F1-score.

## Files in the Repository

- `Loan_Default_Prediction_Model.ipynb`: Jupyter Notebook containing all the code and analysis.
- `Task 3 and 4_Loan_Data.csv`: Dataset used for model training and testing.

## Requirements

- Python 3.x
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
