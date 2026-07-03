# 🍵 Coffee Shop Sales — Exploratory Data Analysis

## Project Overview
Every transaction tells a story, but meaningful business decisions come from turning thousands of records into actionable insights.

This project performs end-to-end data cleaning and exploratory data analysis on a real-world Coffee Shop Sales dataset from Maven Analytics using Python to uncover sales trends, customer purchasing patterns, product performance, and opportunities for business improvement.


## Project Flow
Raw Data → Data Cleaning (Pandas) → Exploratory Data Analysis (Pandas) → Visualization (Matplotlib + Seaborn) → Business Insights & Recommendations


## 🔎 Key Insights Discovered
1. **Product Demand :** Coffee and Tea account for over 69% of total units sold, making them the primary sales drivers. Expanding seasonal variants and bundling them with lower-selling products could help increase overall sales.

2. **Sales Trend :** December initially appeared to be the weakest month for revenue. A closer inspection revealed that the dataset contains only six days of December transactions, making the apparent decline a result of incomplete data rather than poor sales performance.

3. **Revenue Driver :** Correlation analysis shows that unit price (0.69) has a stronger relationship with revenue than quantity sold (0.36). This suggests that promoting higher-value products may have a greater impact on revenue growth than focusing only on increasing sales volume.

4. What is the typical customer order size?

Most customers purchase one or two items per transaction. Introducing combo offers, such as a coffee with a snack, could encourage customers to increase their average order value.

## Tech Stack

The project was built using the following tools and technologies:

- Python - Core programming language used for data analysis.
- Pandas - Data cleaning, preprocessing, feature engineering, data aggregation, and exploratory data analysis (EDA).
- Matplotlib - Created charts to analyze sales trends and product performance.
- Seaborn - Built statistical visualizations, including distributions and correlation analysis.

## Conclusion
This project demonstrates how end-to-end exploratory data analysis can transform raw transaction data into actionable business insights.