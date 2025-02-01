# Loan Risk Prediction

## Project Overview

This project focuses on predicting loan default risk using machine learning. The goal is to help financial institutions assess the creditworthiness of applicants and mitigate financial risks by leveraging data-driven decision-making.

## Objective

The objective of this project is to build a classification model that predicts whether a loan applicant is likely to default or repay the loan based on historical data.

## Dataset

The Lending Club dataset contains complete loan data for all loans issued through the 2007-2015, including the current loan status (Current, Late, Fully Paid, etc.) and latest payment information. Features (aka variables) include credit scores, number of finance inquiries, address including zip codes and state, and collections among others. Collections indicates whether the customer has missed one or more payments and the team is trying to recover their money. The file is a matrix of about 890 thousand observations and 75 variables.

Download the Lending Club Loan Dataset from the provided source - https://www.kaggle.com/datasets/adarshsng/lending-club-loan-data-csv/data

## Approach

### Data Preprocessing

1. Handling missing values

2. Encoding categorical features

3. Feature scaling (StandardScaler for numerical features)

### Exploratory Data Analysis (EDA)

1. Distribution of loan status

2. Correlation analysis between features

3. Identifying key factors influencing loan defaults

### Model Selection & Training

#### Models tried:

- Logistic Regression

- Random Forest

- XGBoost

- LightGBM

### Evaluating models using accuracy, precision, recall, and F1-score

Hyperparameter tuning using GridSearchCV/RandomizedSearchCV (WIP)

#### Model Evaluation

- Generating confusion matrix

- ROC-AUC analysis to compare model performance

- Addressing class imbalance issues (WIP)

### Results (WIP)

- The best-performing model achieved an accuracy of XX%, with a precision-recall tradeoff optimized for detecting high-risk applicants.

- Feature importance analysis revealed that credit score, debt-to-income ratio, and loan amount were the top predictors of loan default.

### Technologies Used

- Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)

- Machine Learning Models (Logistic Regression, Random Forest, XGBoost, etc.)

- Data Preprocessing (OneHotEncoder, StandardScaler)

- Visualization (Matplotlib, Seaborn)

### How to Run the Project

- Clone the repository

- Run Loan Risk Prediction Project.ipynb

### Future Improvements

- Implementing deep learning models (Neural Networks)

- Enhancing feature engineering techniques

- Deploying as a cloud-based API