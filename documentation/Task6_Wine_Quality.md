# Task 6 — Wine Quality Prediction

## Overview

This task focuses on predicting wine quality using physicochemical
properties of wine.

The dataset contains both red and white wine samples.

## Dataset

**Dataset:** Wine Quality Dataset

**File:** `wine-quality-white-and-red.csv`

### Dataset Size

- Rows: 6,497
- Columns: 13

## Features

The dataset contains:

- Type
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

### Target

`quality`

## Objectives

The objectives were:

1. Explore wine-quality data.
2. Inspect missing values and distributions.
3. Prepare features for machine learning.
4. Create a quality prediction model.
5. Evaluate classification performance.
6. Compare model results.

## Data Preprocessing

The preprocessing included:

- Checking data types.
- Checking missing values.
- Separating features and target.
- Encoding the wine type feature.
- Scaling numerical features where required.
- Preparing training and testing data.

## Models

The classification models include:

- Logistic Regression
- Random Forest

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

## Analysis

The models were compared to determine their ability to predict wine
quality from the available physicochemical features.

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Conclusion

This task demonstrates how machine learning can be applied to
predict wine quality using measurable chemical and physical
properties of wine.
