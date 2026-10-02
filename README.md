# Credit Card Fraud Detection

## Project Overview

This project focuses on detecting fraudulent credit card transactions using
machine learning classification techniques.

The project uses three machine learning models:

- Logistic Regression
- Random Forest
- XGBoost

## Objectives

- Analyze credit card transaction data
- Identify fraudulent transactions
- Handle class imbalance using SMOTE
- Train multiple classification models
- Compare model performance

## Dataset

The project uses the Credit Card Fraud Detection dataset.

The dataset contains transaction-related features including:

- Time
- V1 to V28
- Amount
- Class

The `Class` column is the target variable:

- `0` → Normal transaction
- `1` → Fraudulent transaction

> The dataset file is not included in this repository because of its large size.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn
- Jupyter Notebook

## Machine Learning Workflow

1. Data Loading
2. Data Inspection
3. Exploratory Data Analysis
4. Class Imbalance Analysis
5. Train-Test Split
6. Feature Scaling
7. SMOTE for Handling Class Imbalance
8. Model Training
9. Model Evaluation
10. Model Comparison

## Models

### Logistic Regression

Used as a baseline classification model for fraud detection.

### Random Forest

An ensemble-based classification algorithm used to identify fraudulent transactions.

### XGBoost

A gradient boosting algorithm used for classification and performance comparison.

## Evaluation Metrics

The models were evaluated using:

- Precision
- Recall
- F1 Score
- Accuracy
- Confusion Matrix
- Classification Report

## Results

| Model | Precision | Recall | F1 Score | Accuracy |
|---|---:|---:|---:|---:|
| Logistic Regression | 0.0578 | 0.9184 | 0.1088 | 0.9741 |
| Random Forest | 0.8667 | 0.7959 | 0.8298 | 0.9994 |
| XGBoost | 0.2522 | 0.8776 | 0.3918 | 0.9953 |

## Project Structure

```text
Credit-Card-Fraud-Detection/
│
├── Credit_Card_Fraud_Detection.ipynb
└── README.md
