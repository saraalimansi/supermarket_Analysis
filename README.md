# Supermarket Sales Analysis

This project involves cleaning and analyzing a **supermarket sales dataset** to uncover patterns and trends in sales performance.
 The analysis was performed using Python, and the cleaned dataset is included alongside the original for reproducibility.

---

## Key Features Analyzed
The dataset includes several important metrics such as:
- **Unit Price**: The price per unit of a product.
- **Quantity**: The number of units purchased.
- **Total**: Total sales value for a transaction.
- **Tax 5%**: The tax applied to the sales.
- **Gross Income**: The profit made on each transaction.
- **Rating**: Customer satisfaction rating for a purchase.

---

## Key Insights

Correlation Analysis:

Strong correlations were found between:
Tax 5% and Total (expected as tax is calculated on total sales).
Gross Income and Total.
Customer Behavior:

Certain times of the day exhibited higher sales volume (e.g., afternoon peak hours).
Ratings showed minimal correlation with sales metrics.
Product Trends:

Higher unit price products were associated with higher profits.
## Project Overview

The project is divided into two main parts:

1. **Data Cleaning**:
   - The raw dataset (`supermarket_sales.csv`) contained inconsistent values.
   - Cleaning steps included:
     - Handling missing data.
     - Converting time formats (e.g., from 24-hour format to 12-hour format).
     - Ensuring consistency in numerical and categorical columns.
   - The cleaned dataset (`supermarket_Analysis_cleaned.csv`) is included for further analysis.

2. **Data Analysis**:
   - Exploratory Data Analysis (EDA) was conducted to identify trends and insights.
   - Key analyses included:
     - Correlation between numerical features.
     - Time-based sales analysis (e.g., sales distribution by hours).
     - Identifying customer behavior patterns.
   - Visualizations were generated to illustrate findings.

---

## Files and Folders

- **`data/supermarket_sales.csv`**: The original raw dataset.
- **`data/supermarket_Analysis_cleaned.csv`**: The cleaned dataset after preprocessing.
- **`scripts/supermarket_analysis.ipynb`**: Python script used for cleaning and analyzing the dataset.
- **`outputs/`**: Contains visualizations and analysis results (e.g., heatmaps, bar plot).
- **`report.html`**: Interactive report summarizing the analysis.


The dataset was provided by kaggle.com.
Analysis and visualizations were performed using Python libraries: Pandas, Matplotlib, Seaborn.