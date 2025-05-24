# Sales-data-analysis

# 📊 Analyzing Amazon Sales Data

## 🧠 Project Overview
This project aims to analyze Amazon sales data to discover important business trends and insights. By performing ETL (Extract-Transform-Load), we explore monthly and yearly sales patterns, calculate key metrics, and identify meaningful relationships between features like revenue, profit, units sold, and item types. The goal is to help improve decision-making in e-commerce sales strategies.

---

## 🛠️ Technologies Used
- **Python** for data cleaning, transformation, and analysis
  - `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Power BI** for interactive dashboards and insights
- **Jupyter Notebook / VS Code** for development

---

## 🗂️ Dataset Columns
The dataset includes the following fields:

- `Region`
- `Country`
- `Item Type`
- `Sales Channel`
- `Order Priority`
- `Order Date`
- `Order ID`
- `Ship Date`
- `Units Sold`
- `Unit Price`
- `Unit Cost`
- `Total Revenue`
- `Total Cost`
- `Total Profit`

---

## 🔄 ETL Process
- **Extract**: Loaded the dataset from CSV format.
- **Transform**:
  - Converted `Order Date` and `Ship Date` into datetime objects.
  - Extracted `Month`, `Year`, and `Month-Year` from `Order Date`.
  - Cleaned missing or duplicate records.
  - Created new metrics where needed (e.g., `Profit Margin`, `Revenue per Unit`).
- **Load**: Used cleaned DataFrame for analysis and visualizations.

---

## 📈 Sales Trend Analysis
- **Month-wise Sales**: Total Revenue and Profit per month.
- **Year-wise Sales**: Growth or decline in revenue/profit over the years.
- **Yearly Month-wise Trends**: Seasonal analysis using heatmaps.

---

## 📌 Key Metrics
- **Total Revenue** = Sum of `Total Revenue`
- **Total Profit** = Sum of `Total Profit`
- **Average Unit Price**
- **Units Sold by Category**
- **Most Profitable Item Types**
- **Performance by Region and Country**

---

## 🔍 Insightful Relationships
- Correlation between `Units Sold` and `Total Profit`
- Price vs. Profitability
- Region-wise demand vs. fulfillment efficiency
- Impact of order priority on delivery time and profit

---

## 📊 Visualizations
- Line plots for sales trends (month/year)
- Bar charts for top item types by revenue/profit
- Heatmaps for monthly sales patterns
- Pie charts for regional distribution

---

