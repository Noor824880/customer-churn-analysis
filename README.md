# customer-churn-analysis
📊 Customer Churn Analysis — Python &amp; SQL Analyzed 10,000 telecom records using Python (Pandas, NumPy, Matplotlib) and SQL queries. Built 12 visualizations, segmented customers by churn risk, and found 68% churn among month‑to‑month contracts. Delivered actionable retention insights.
# Customer Churn Analysis — Python & SQL
[![Python](https://img.shields.io/badge/Python-3.x-blue)]
[![SQL](https://img.shields.io/badge/SQL-MySQL-orange)]
## Overview
End-to-end analysis of a 10,000-row telecom customer dataset to identify churn drivers
using Python (Pandas, NumPy, Matplotlib) and SQL (JOINs, window functions, subqueries).
## Project Structure
customer-churn-analysis/
|- notebooks/ churn_eda.ipynb # Full EDA notebook
|- sql/ churn_queries.sql # 15+ SQL queries
|- data/ telecom_churn.csv # Source dataset
|- charts/ [12 PNG visualisations]
|- README.md
## Key Tools- Python: Pandas, NumPy, Matplotlib, Jupyter- SQL: JOINs, Subqueries, GROUP BY, CASE WHEN, Window Functions
## Key Insights- 68% of churned customers were on month-to-month contracts- Customers with tenure < 12 months and charges > $70 = highest churn risk- Fibre optic subscribers churned at higher rates despite higher spend- Correlation: tenure vs churn = -0.35 | monthly charges vs churn = +0.19
## How to Run
pip install pandas numpy matplotlib
jupyter notebook notebooks/churn_eda.ipynb
## Screenshots
![Overview Dashboard](charts/c1_churn_overview.png)
![EDA Analysis](charts/c2_eda_distributions.png)
![SQL Analysis](charts/c3_sql_analysis.png)
