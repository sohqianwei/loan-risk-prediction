# Loan Risk Prediction

## Project Overview

This project focuses on predicting loan default risk using machine learning. The goal is to help financial institutions assess the creditworthiness of applicants and mitigate financial risks by leveraging data-driven decision-making.

## Objective

The objective of this project is to build a classification model that predicts whether a loan applicant is likely to default or repay the loan based on historical data.

## Dataset

This dataset contains the full LendingClub data available from their site. Icluding the current loan status (Current, Late, Fully Paid, etc.) and latest payment information. Features (aka variables) include credit scores, number of finance inquiries, address including zip codes and state, and collections among others. Collections indicates whether the customer has missed one or more payments and the team is trying to recover their money. The file is a matrix of about 890 thousand observations and 75 variables. There are separate files for accepted and rejected loans. 

Loan - Credit Risk & Population Stability is a part of Lending Club Company public database:
https://www.kaggle.com/datasets/beatafaron/loan-credit-risk-and-population-stability/data


## Approach

### Data Preprocessing

1. Handling missing values

2. Encoding categorical features

3. Managing Date Features

4. Imputing Values for Missing Numerical Features

### Exploratory Data Analysis (EDA)

1. Correlation analysis between features

2. Selection based on Correlation with Target Feature

3. Feature Selection with Recursive Feature Elimination


### Model Selection & Training

#### Models tried:

- Logistic Regression

- Random Forest

- Gradient Boost

- Neural Networks


#### Model Evaluation

- Generating confusion matrix

- ROC-AUC analysis to compare model performance


### Results 

- The best-performing model achieved an accuracy of XX%, with a precision-recall tradeoff optimized for detecting high-risk applicants.

- Feature importance analysis revealed that recoveries, debt settlement flag, total_rec_prncp were the top predictors of loan default.

### Technologies Used

- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)

- Machine Learning Models (Logistic Regression, Random Forest, Gradient Boost, etc.)

- Data Preprocessing

- Visualization (Matplotlib, Seaborn)

### How to Run the Project

- Clone the repository

- Run loan_risk_modelling.ipynb

### Future Improvements

- Implementing XGBoost

- Enhancing feature engineering techniques

- Deploying as a cloud-based API