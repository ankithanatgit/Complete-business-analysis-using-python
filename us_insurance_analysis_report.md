# US Insurance Data Analysis Report

## Overview
This report summarizes insights derived from the US Insurance dataset and the visualizations generated from it.
The analysis focuses on understanding customer behavior, numeric feature distributions, correlations, and churn patterns.

## Dataset Summary
The dataset contains customer-level numeric attributes such as:
- Tenure
- Monthly Charges
- Total Charges
- Churn (target variable)

Only numeric columns were used for visualization and correlation analysis.

## Visualizations Generated

### 1. Feature Distribution Plots
Histograms were generated for key numeric features:
- Tenure Distribution
- Monthly Charges Distribution
- Total Charges Distribution

These plots help identify skewness, outliers, and general data spread.

### 2. Correlation Matrix
A correlation matrix was created to understand relationships between numeric features.
Strong correlations indicate features that influence each other and may impact churn behavior.

### 3. Churn Count Plot
A bar chart shows the count of customers who churned versus those who retained service.
This gives a quick view of class imbalance in the dataset.

## Key Insights
- Monthly and Total Charges show strong correlation with customer tenure.
- Customers with shorter tenure and higher monthly charges show higher churn probability.
- The dataset has churn imbalance, meaning fewer churn cases compared to retained users.

## Business Interpretation
- Customers with high monthly charges and low tenure are at higher risk.
- Long-tenure customers are more stable and should be targeted for loyalty programs.
- High correlation features should be carefully selected during modeling to avoid redundancy.

## Conclusion
The visual analysis provides strong evidence that tenure, monthly charges, and total charges are critical indicators of churn risk.
These insights can guide customer retention strategies and predictive modeling efforts.