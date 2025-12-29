US Insurance Customer Analysis & Churn Segmentation
📌 Project Overview

This project analyzes a US insurance customer dataset to understand customer behavior, visualize important trends, segment customers into meaningful groups, and predict churn using machine learning models.

The project helps businesses identify high-risk customers and design targeted retention strategies.

🎯 Objectives

Perform exploratory data analysis on insurance customer data.

Generate visual insights using histograms, correlation matrix, and churn count plots.

Segment customers using clustering algorithms.

Build separate churn prediction models for each customer segment.

Provide actionable business recommendations.

🗂 Project Structure
project/
│
├── visualizations/
│   ├── tenure_distribution.png
│   ├── monthly_charges_distribution.png
│   ├── total_charges_distribution.png
│   ├── correlation_matrix.png
│   └── churn_count.png
│
├── report/
│   └── us_insurance_analysis_report.md
│
├── US_insurance_Analysis.ipynb
├── requirements.txt
└── README.md

🛠 Technologies Used
Category	Tools
Language	Python
Libraries	Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
IDE	Google Colab / Jupyter Notebook
Models	K-Means, Agglomerative Clustering, Random Forest
📊 Visualizations

Feature distribution plots for tenure, monthly charges, and total charges.

Correlation matrix to identify relationships between variables.

Churn count plot to show retained vs churned customers.

🔍 Key Insights

Tenure, monthly charges, and total charges are highly correlated.

Customers with high monthly charges and low tenure have higher churn risk.

Loyal customers form a large segment with very low churn probability.

💡 Business Recommendations
Segment	Strategy
High Churn Risk	Proactive retention calls, special offers
Price Sensitive	Discounts, flexible pricing plans
Loyal Customers	Loyalty rewards, upselling premium services
▶ How to Run
pip install -r requirements.txt


Open and run the notebook:

US_insurance_Analysis.ipynb

🏁 Conclusion

This project demonstrates how customer segmentation combined with machine learning can help businesses improve customer retention, boost revenue, and make data-driven decisions.
