## Overview
This repository contains the work I completed during my virtual internship in Quantitative Research at JPMorgan Chase & Co., facilitated through Forage. The project focused on developing a predictive model for assessing credit risks associated with personal loans. The rising default rates on these loans posed a significant challenge, and through this project, I developed a logistic regression model to predict default probabilities based on borrower data.

## Project Objective
The primary objective of this project was to estimate the probability of default on personal loans using historical data, thereby enabling the bank to make informed decisions regarding loan approvals and risk management.

## Data Description
The dataset provided by JPMorgan included various borrower characteristics such as income levels, total loans outstanding, FICO scores, and previous default history. Feature engineering was performed to create additional metrics like Debt-to-Income (DTI) and Payment-to-Income (PTI) ratios to better assess the financial health of borrowers.

## Tools and Technologies
- **Python**: Primary programming language used for data analysis and model building.
- **Pandas**: Used for data manipulation and cleaning.
- **Scikit-Learn**: Employed for creating the logistic regression model and evaluating its performance.
- **Matplotlib**: Utilized for data visualization.

## Model Description
A logistic regression model was developed to predict the likelihood of default. The model's performance was evaluated using accuracy and ROC-AUC score, achieving 99% accuracy and a 0.9995 ROC-AUC score, indicating excellent capability in distinguishing between defaulters and non-defaulters.

## Results
The model demonstrated high reliability in predicting default events, which can significantly aid in enhancing the bank's decision-making process regarding loan approvals and risk mitigation.
