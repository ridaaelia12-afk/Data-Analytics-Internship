# Task 1 — Retail Sales Analysis

## Overview

This task focuses on analyzing a retail sales dataset to identify
sales trends, customer purchasing behavior, and product-category
performance.

The analysis was performed using Python, Pandas, Matplotlib, and
Seaborn in a Kaggle Notebook.

---

## Dataset

**Dataset:** Retail Sales Dataset

The dataset contains 1,000 retail transactions with the following
columns:

- Transaction ID
- Date
- Customer ID
- Gender
- Age
- Product Category
- Quantity
- Price per Unit
- Total Amount

### Dataset Size

- Rows: 1,000
- Columns: 9

---

## Objectives

The main objectives of this task were:

1. Understand the structure of the retail dataset.
2. Clean and prepare the data for analysis.
3. Analyze overall sales performance.
4. Identify the best-performing product categories.
5. Analyze customer purchasing behavior.
6. Examine sales trends over time.
7. Visualize important patterns in the data.

---

## Data Preprocessing

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Examined the dataset structure and data types.
- Checked for missing values.
- Checked for duplicate records.
- Converted the `Date` column into a proper datetime format.
- Verified numerical columns.
- Created additional time-based features where required.

---

## Exploratory Data Analysis

Several aspects of the dataset were analyzed.

### Sales Analysis

Total sales were analyzed using the `Total Amount` column.

The analysis examined:

- Total revenue
- Average transaction value
- Sales distribution
- Number of transactions

### Product Category Analysis

Sales performance was compared across different product categories.

The analysis examined:

- Total sales by category
- Quantity sold by category
- Average sales by category

This helps identify which product categories contribute most to
overall revenue.

### Customer Analysis

Customer purchasing behavior was analyzed using:

- Customer ID
- Gender
- Age
- Quantity purchased
- Total Amount

This provides insight into customer spending patterns.

### Time-Based Analysis

The transaction date was used to analyze sales over time.

Monthly and date-based sales trends were visualized to identify
changes in purchasing activity.

---

## Visualizations

The analysis includes visualizations such as:

- Sales distribution
- Sales by product category
- Quantity by product category
- Customer spending analysis
- Monthly sales trends
- Gender-based sales analysis

These visualizations make it easier to identify patterns and trends
within the retail data.

---

## Key Insights

The analysis can be used to identify:

- Which product categories generate the highest revenue.
- Which categories have the highest sales volume.
- How customer demographics relate to purchasing behavior.
- How sales change over time.
- Differences in purchasing behavior between customer groups.

The exact numerical findings are presented in the Kaggle notebook
outputs.

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Kaggle Notebook

---

## Files

The complete implementation is available in:

`notebooks/Kaggle_Internship_9_Tasks.ipynb`

---

## Conclusion

Task 1 demonstrates the use of exploratory data analysis techniques
to understand retail sales data. The analysis provides insights into
sales performance, customer behavior, product categories, and
temporal sales patterns.

The results can help businesses understand purchasing trends and
support data-driven decisions related to products, customers, and
sales strategies.
