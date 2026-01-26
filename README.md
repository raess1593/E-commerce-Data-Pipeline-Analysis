# 🛒 E-commerce Sales Data Pipeline & Analysis

## 📌 Project Overview
This project demonstrates a professional end-to-end data engineering and analysis pipeline. Using a dataset of 10,000 retail records, it automates the process of extracting raw data, cleaning inconsistencies, and generating business-critical insights. 

**Key Objectives:**
- Build a scalable ETL (Extract, Transform, Load) process.
- Implement advanced data imputation techniques for missing values.
- Analyze customer behavior and sales trends.

## 🛠️ Tech Stack
- **Language:** Python 3.11
- **Primary Library:** Pandas (Advanced Data Wrangling)
- **Numerical Logic:** NumPy (Vectorized Operations)
- **Visualization:** Seaborn & Matplotlib
- **Environment:** Jupyter Notebooks / VS Code

## ⚡ Key Engineering Features
- **Median Imputation:** Automated handling of missing `unit_price` values by grouping by product type to ensure statistical accuracy.
- **Categorical Normalization:** Cleaned inconsistent naming conventions using vectorized string operations.
- **Feature Engineering:** Creation of performance KPIs like `total_revenue` and time-based metrics.
- **Outlier Detection:** Statistical analysis to identify anomalies in sales quantities and prices.

## 📊 Business Insights
*(Note: These will be populated as we complete the visualizations in the notebook)*
- Sales seasonality analysis.
- Product performance ranking.
- Revenue distribution by city.

## 🚀 How to Run
1. Clone the repository.
2. Install dependencies: `pip install pandas numpy seaborn matplotlib openpyxl`.
3. Open `notebooks/E-commerce_Data_Analysis.ipynb` and run all cells.
