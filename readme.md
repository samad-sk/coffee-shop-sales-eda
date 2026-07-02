# Coffee Shop Sales — Exploratory Data Analysis

A comprehensive data cleaning and exploratory data analysis project built to uncover 
sales patterns, product performance, and revenue trends of a New York based coffee 
shop chain using Python.


## Purpose of the Project

Coffee shops generate thousands of transactions daily, yet most small businesses lack 
a clear and structured way to track which products are selling, how each store is 
performing, and how revenue is trending over time.

This project cleans and analyzes a real-world Coffee Shop Sales dataset to uncover product 
performance, store activity, and revenue trends using Python — one of my 
end-to-end project using core python libraries in data analytics.



## Tech Stack

The project was built using the following tools and technologies:

- 🐍 **Python** — Core programming language used throughout the project
- 🐼 **Pandas** — Data cleaning, transformation, groupby analysis and derived columns
- 📊 **Matplotlib** — Static visualizations including bar charts and line charts
- 🎨 **Seaborn** — Statistical visualizations including heatmap, countplot and histplot
- 📓 **Jupyter Notebook** — Interactive development and documentation environment
- 📁 **File Format** — `.ipynb` for notebook, `.csv` for raw and cleaned data, `.png` for charts


## Data Source
**Source:** Maven Analytics

Data on 114,976 coffee shop transactions across 3 New York locations — Astoria, 
Hell's Kitchen and Lower Manhattan — covering the period January 2023 to December 2023, 
including details on transaction date, time, quantity, store location, unit price, 
product category, product type and product detail.


## Business Questions, Insights & Recommendations
**1. Which product category do customers buy the most?**
- Chart Used : Bar Chart
- Insight : Coffee and Tea together account for over 69% of all units sold
- Recommendation : Introduce seasonal coffee and tea variants to maintain demand. Bundle them with low selling items like Packaged Chocolate and Flavours to boost their sales.

**2. Which store location generates the most revenue?**
- Chart Used : Column Chart
- Insight : All 3 stores perform almost equally — similar sales, revenue and transactions. No single store is significantly ahead or behind.
- Recommendation : Focus on reducing operation costs to improve profit margin. Consistent performance in store model is ideal for expanding to new locations.

**3. How did revenue change month over month?**
- Chart Used : Line Chart
- Insight : Revenue grew steadily from January to June, peaking around May-June. The  drop in December is due to incomplete data — only 6 days of December are recorded.
- Recommendation : Run special offers before May-June to maximize peak sales. During slow months, introduce discounts and repeat customer deals to maintain revenue.

**4. Which store is most active ?**
- Chart Used : Countplot
- Insight : All stores are equally active and receive similar number of orders. No single store dominates in customer footfall. 
- Recommendation : Since data shows active customer demands. Business can expand and introduce branches in other locations.

**5. Which factors — quantity ordered or unit price — have a stronger impact on revenue?**
- Chart Used : Heatmap
- Insight : Unit price has a stronger impact on revenue (0.69) than quantity ordered (0.36) — meaning selling higher priced products matters more than selling more items."
- Recommendation : Focus on promoting premium and higher priced products like coffee beans and branded items to increase revenue.

**6. What is the typical order size of a customer per transaction?**
- Chart Used : Histogram
- Insight : Most customers order only 1 or 2 items per transaction. 
- Recommendation : Introduce combo offers like 'Coffee + Snack' deals to encourage customers to buy more items per visit.

## Conclusion

This project performed end-to-end data cleaning and exploratory data analysis on a 
real-world Coffee Shop Sales dataset using Python. The analysis revealed that Coffee 
and Tea drive the majority of the business, all 3 store locations perform consistently, 
and unit price impacts revenue more than order quantity. These findings provide a 
clear picture of where the business stands and where it can improve.