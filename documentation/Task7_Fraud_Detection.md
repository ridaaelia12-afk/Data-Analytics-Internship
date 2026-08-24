# Task 7 — Credit Card Fraud Detection

## Overview

This task focuses on detecting fraudulent credit card transactions
using machine learning.

Fraud detection is treated as a binary classification problem.

## Dataset

**Dataset:** Credit Card Fraud Detection Dataset

**File:** `creditcard.csv`

### Dataset Size

- Rows: 284,807
- Columns: 31

### Target

`Class`

The target represents whether a transaction is fraudulent or
non-fraudulent.

## Objectives

The objectives were:

1. Explore the transaction dataset.
2. Identify the class distribution.
3. Prepare the features.
4. Train classification models.
5. Evaluate fraud detection performance.
6. Analyze model predictions.

## Data Preprocessing

The preprocessing included:

- Checking data types.
- Checking missing values.
- Separating features and target.
- Splitting data into training and testing sets.
- Scaling appropriate numerical features where required.

## Class Imbalance

Fraud detection datasets are typically highly imbalanced, with
fraudulent transactions representing a much smaller proportion of
the data.

Therefore, evaluation should not rely only on accuracy.

## Models

The models include:

- Logistic Regression
- Random Forest

## Evaluation Metrics

The models were evaluated using:

- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Importance of Recall

Recall is particularly important in fraud detection because failing
to identify a fraudulent transaction can have significant
consequences.

Precision is also important because incorrectly identifying
legitimate transactions as fraudulent can negatively affect
customers.

## Visualization

Confusion matrices and other evaluation visualizations were used
to analyze model performance.

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Conclusion

This task demonstrates the application of machine learning to
financial fraud detection and highlights the importance of using
appropriate evaluation metrics for imbalanced classification
problems.
