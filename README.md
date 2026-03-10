<<<<<<< HEAD
# Fraud Detection Using Machine Learning

## Overview
This project builds machine learning models to detect fraudulent credit card transactions. Fraud detection is challenging because fraudulent transactions are extremely rare compared to legitimate transactions.

The goal of this project is to compare multiple machine learning models and determine which approach best detects fraud while minimizing false positives.

## Dataset
Credit Card Fraud Detection Dataset from Kaggle.

- Total transactions: 284,807
- Fraud cases: 492
- Fraud rate: ~0.17%

## Models Implemented
- Logistic Regression
- Weighted Logistic Regression
- SMOTE Logistic Regression
- Random Forest
- XGBoost

## Evaluation Metrics
Because fraud datasets are highly imbalanced, accuracy is not a useful metric. Instead we evaluate models using:

- Precision
- Recall
- F1 Score
- ROC-AUC

## Results
The SMOTE Random Forest model produced the best balance between precision and recall, making it the most effective model for fraud detection.

## Project Structure
=======
# Fraud Detection Using Machine Learning

This project builds a machine learning system to detect fraudulent credit card transactions.

## Objective

Fraud detection is challenging because fraudulent transactions are extremely rare. The goal of this project is to build models that accurately detect fraud while minimizing false positives.

## Dataset

Credit Card Fraud Detection Dataset from Kaggle.

Transactions: 284,807  
Fraud Cases: 492

## Models Used

- Logistic Regression
- Weighted Logistic Regression
- SMOTE Logistic Regression
- Random Forest
- XGBoost

## Evaluation Metrics

- Precision
- Recall
- F1 Score
- ROC-AUC

## Key Results

The SMOTE Random Forest model achieved the best balance between precision and recall, making it the most effective fraud detection model.

## Tools Used

Python  
Scikit-learn  
XGBoost  
Pandas  
Matplotlib

>>>>>>> 94f3de027c1da56734dbf3e51d4bf3e5ccc17420
