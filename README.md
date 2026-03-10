# 🍜 Swiggy Sales Analysis — EDA with Python

An end-to-end Exploratory Data Analysis (EDA) project on Swiggy food delivery data, covering revenue trends, customer behaviour, and geographic performance using **Pandas**, **Matplotlib**, **Seaborn**, and **Plotly**.

---

## 📌 Problem Statement

The goal of this project is to analyse Swiggy's sales data and derive actionable insights across KPIs such as revenue, order volume, customer ratings, and food preferences — segmented by time, geography, and food category.

---

## 📊 KPIs Tracked

| KPI | Description |
|-----|-------------|
| **Total Sales (₹)** | Overall revenue generated from food orders |
| **Average Rating** | Customer satisfaction level across all restaurants |
| **Average Order Value (₹)** | Revenue per order placed |
| **Ratings Count** | Total number of customer reviews submitted |
| **Total Orders** | Number of food orders received in the dataset |

---

## 📈 Charts & Visualisations

| Chart | What It Shows |
|-------|---------------|
| **Monthly Sales Trend** | How total revenue fluctuates month by month |
| **Daily Sales Trend** | Order and revenue variation across days of the week (Mon–Sun) |
| **Veg vs Non-Veg Revenue** | Revenue split between vegetarian and non-vegetarian orders (Donut chart) |
| **Total Sales by State** | State-wise revenue distribution (Horizontal bar chart) |
| **Quarterly Performance Summary** | Sales, ratings, and order count grouped by quarter |
| **Top 5 Cities by Sales** | Highest revenue-generating cities |
| **Weekly Trend Analysis** | Weekly sales fluctuations to identify peak periods |

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data loading, cleaning, and aggregation
- **NumPy** — numerical operations
- **Matplotlib** — static charts (line, bar)
- **Seaborn** — styled statistical plots
- **Plotly Express** — interactive charts (pie/donut, bar)

---

## 📁 Project Structure

```
swiggy-sales-analysis/
│
├── Swiggy_Sales_Analysis.ipynb    # Main Jupyter Notebook with EDA
├── swiggy_data.xlsx               # Source dataset 
└── README.md                      # Project documentation
```
---

## 💡 Key Insights (Sample)

- Revenue shows clear **monthly seasonality**, with spikes around weekends and festive periods.
- **Non-Veg orders** contribute a significant share of total revenue despite fewer unique SKUs.
- A handful of **metro cities** dominate overall sales, while Tier-2 cities show growth potential.
- **Q3 and Q4** typically outperform earlier quarters in both orders and ratings.

---

## 🙋 About

This project was built as part of a data analytics learning journey, focusing on real-world EDA workflows — from raw data ingestion and cleaning to multi-dimensional visual storytelling.

Feel free to fork, explore, or raise issues!

---

*Built with 🧡 using Python & Jupyter*
