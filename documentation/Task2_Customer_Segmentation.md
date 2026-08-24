# Task 2 — Customer Segmentation Using RFM and K-Means

## Overview

This task focuses on segmenting retail customers based on their
purchasing behavior.

RFM analysis was used to calculate:

- Recency
- Frequency
- Monetary Value

K-Means clustering was then applied to group customers with similar
purchasing characteristics.

## Dataset

**Dataset:** Retail Sales Dataset

**File:** `retail_sales_dataset.csv`

## Objectives

The main objectives were:

1. Calculate customer Recency.
2. Calculate customer Frequency.
3. Calculate customer Monetary value.
4. Prepare RFM features.
5. Standardize the features.
6. Determine a suitable number of clusters.
7. Apply K-Means clustering.
8. Analyze customer segments.

## RFM Analysis

### Recency

Recency measures how recently a customer made a purchase.

A lower recency value generally represents a more recently active
customer.

### Frequency

Frequency represents the number of transactions made by a customer.

### Monetary

Monetary represents the total amount spent by a customer.

## Preprocessing

The dataset was prepared by:

- Converting transaction dates to datetime format.
- Removing records with missing customer/date/sales information.
- Keeping valid positive sales values.
- Aggregating transactions at customer level.
- Creating RFM features.

## Customer Segmentation

RFM features were standardized before clustering.

The Elbow Method was used to examine different values of K.

K-Means clustering was then applied to assign customers to segments.

## Cluster Analysis

The resulting clusters were analyzed using:

- Average Recency
- Average Frequency
- Average Monetary value
- Cluster size

Visualizations were created to compare customer segments.

## Business Interpretation

The segments can be used to identify:

- High-value customers.
- Frequent customers.
- Recently active customers.
- Customers requiring re-engagement.
- Lower-value customer groups.

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Conclusion

RFM analysis combined with K-Means clustering provides a practical
approach for understanding customer behavior and developing
customer-focused marketing strategies.
