# Task 4 — IMDB Movie Review Sentiment Analysis

## Overview

This task focuses on classifying movie reviews according to their
sentiment.

Natural Language Processing techniques were used to convert review
text into numerical features, followed by machine learning
classification.

## Dataset

**Dataset:** IMDB Dataset

**File:** `IMDB Dataset.csv`

### Dataset Size

- Rows: 50,000
- Columns: 2

### Columns

- `review`
- `sentiment`

The sentiment labels contain positive and negative reviews.

## Objectives

The objectives were:

1. Load and inspect the review dataset.
2. Clean the review text.
3. Convert text into numerical features.
4. Split the data into training and testing sets.
5. Train classification models.
6. Evaluate model performance.
7. Compare classification results.

## Text Preprocessing

The review text was processed by:

- Converting text to lowercase.
- Removing URLs where applicable.
- Removing unnecessary characters.
- Removing extra whitespace.
- Preparing text for vectorization.

## Feature Extraction

TF-IDF vectorization was used to transform review text into numerical
features.

Both unigram and bigram features were considered.

## Machine Learning Models

Two classification models were used:

### Naive Bayes

Multinomial Naive Bayes was trained on the TF-IDF representation.

### Logistic Regression

Logistic Regression was also trained and evaluated.

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Visualization

Confusion matrices were generated to examine correct and incorrect
predictions for each sentiment class.

## Tools

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- TF-IDF

## Conclusion

This task demonstrates how Natural Language Processing and machine
learning can be combined to classify movie reviews according to
sentiment.
