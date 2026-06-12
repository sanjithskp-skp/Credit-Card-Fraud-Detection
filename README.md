# Credit Card Fraud Detection

## Project Overview

This project detects fraudulent credit card transactions using Machine Learning.

## Dataset

Credit Card Fraud Detection dataset from Kaggle.

## Problem

The dataset is highly imbalanced:

- Normal: 99.8%
- Fraud: 0.2%

To solve this, SMOTE was applied before training.

## Models Used

- Random Forest
- XGBoost
- LightGBM

## Techniques

- SMOTE
- Threshold Tuning
- ROC-AUC
- Precision
- Recall
- F1 Score

## Best Model

LightGBM

## Results

Accuracy: 99.5%

ROC-AUC: 0.98

## Libraries

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- LightGBM
- Imbalanced-learn