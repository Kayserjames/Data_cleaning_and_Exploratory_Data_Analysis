# 🛒 Data_cleaning_and_Exploratory_Data_Analysis

## 📌 Project Overview

This project focuses on the analysis of an e-commerce transactions dataset using Python. The objective was to transform raw and inconsistent data into reliable business insights through a complete data analytics workflow, including data cleaning, exploratory data analysis (EDA), and data visualization.

This project was completed as part of my internship at AnalystLab Africa.

---

## 🎯 Objectives

- Assess and improve data quality.
- Identify sales trends and customer purchasing patterns.
- Discover top-performing products and markets.
- Generate actionable business insights through data analysis.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🧹 Data Cleaning Process

### Handling Missing Values

- Replaced missing `CustomerID` values with `"Unknown"`.
- Removed records with missing product descriptions.

### Duplicate Detection

- Identified and removed duplicate transactions.

### Data Validation

- Detected negative values in `Quantity` and `UnitPrice`.
- Replaced invalid quantities using the median value calculated per product.

### Outlier Treatment

- Applied the Interquartile Range (IQR) method.
- Removed extreme observations likely to bias the analysis.

## 🔍 Key Insights

### Top Products

Decorative and seasonal products generated a significant share of total sales.

### Sales Seasonality

Sales increased considerably during the last quarter of the year.

### Geographic Performance

The United Kingdom generated the largest share of revenue.


## 📚 Skills Demonstrated

- Data Cleaning
- Data Validation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Business Insight Generation
