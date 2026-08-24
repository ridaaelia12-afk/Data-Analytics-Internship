# Task 8 — Google Play Store Analysis

## Overview

This task focuses on analyzing Google Play Store applications to
identify patterns related to app categories, ratings, reviews,
install counts, pricing, and other application characteristics.

## Dataset

**Dataset:** Google Play Store Apps and Reviews Dataset

**File:** `apps.csv`

### Dataset Size

- Rows: 9,659
- Columns: 14

## Columns

The dataset contains:

- App
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price
- Content Rating
- Genres
- Last Updated
- Current Ver
- Android Ver

An additional index column (`Unnamed: 0`) is also present.

## Objectives

The objectives were:

1. Explore the Google Play Store dataset.
2. Clean the application data.
3. Analyze app categories.
4. Analyze ratings.
5. Analyze installation counts.
6. Study reviews.
7. Compare free and paid applications.
8. Visualize important patterns.

## Data Preprocessing

The preprocessing included:

- Inspecting data types.
- Checking missing values.
- Removing or handling unnecessary index columns.
- Cleaning numeric fields such as installs and prices.
- Preparing the dataset for analysis.

## Exploratory Analysis

The analysis examines:

- App distribution by category.
- Rating distribution.
- Review counts.
- Installation ranges.
- Free versus paid apps.
- Content ratings.
- Genres.
- App sizes where available.

## Important Dataset Limitation

The supplied `apps.csv` dataset contains **app-level information**.

It does not provide individual review text with sentiment labels in
the same table.

Therefore, individual review sentiment classification cannot be
reliably performed using only this supplied app-level dataset.

The analysis is therefore focused on the information actually
available in the dataset.

## Visualizations

Visualizations include analyses of:

- App categories.
- Ratings.
- Install counts.
- Free and paid applications.
- Content ratings.
- Review counts.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Conclusion

This task demonstrates how app-store data can be analyzed to
understand application popularity, ratings, categories, pricing,
and other characteristics.
