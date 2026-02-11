Customer Churn Prediction

Project Overview

This project predicts customer churn using machine learning techniques. The goal is to identify customers likely to leave and help businesses take preventive actions.

Dataset

Telco Customer Churn Dataset from Kaggle.

Techniques Used

Data Cleaning

Exploratory Data Analysis

Feature Engineering

SMOTE (Handling Imbalance)

Random Forest

XGBoost

ROC-AUC Evaluation

| Model         | ROC-AUC |
| ------------- | ------- |
| Random Forest | 0.88    |
| XGBoost       | 0.91    |

Key Business Insights

Month-to-month customers churn more.

Low tenure customers are high risk.

High monthly charges increase churn.

Fiber optic users show higher churn.

Lack of tech support increases churn.

How to Run
pip install -r requirements.txt
