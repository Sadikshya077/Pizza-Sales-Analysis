# 🍕 Pizza Sales Analysis

## Overview

This project analyzes transactional pizza sales data to identify key sales patterns, product performance, customer purchasing behavior, and business opportunities.

The analysis focuses on key performance indicators (KPIs), sales trends by day, month, and hour, pizza category and size performance, and the best- and worst-performing pizza products.

The project was developed using Python and focuses on turning transactional data into actionable business insights and recommendations.

---

## 🎯 Business Objectives

The project aims to:

- Measure overall sales performance using key KPIs
- Analyze revenue and quantity sold across pizza categories
- Understand customer demand by pizza size
- Identify daily, monthly, and hourly sales trends
- Identify the highest- and lowest-performing pizza products
- Understand customer purchasing behavior through AOV and pizzas per order
- Provide actionable recommendations for sales, inventory, staffing, and menu decisions

---

## 📊 Key Performance Indicators

| KPI | Result |
|---|---:|
| **Total Revenue** | **$817,860.05** |
| **Total Pizzas Sold** | **49,574** |
| **Total Orders** | **21,350** |
| **Average Order Value** | **$38.31** |
| **Average Pizzas per Order** | **2.32** |

---

## 🔎 Analysis Performed

### Sales Trends

The analysis examines sales across:

- Day of the week
- Hour of the day
- Month

### Product Analysis

The project analyzes:

- Sales by pizza category
- Sales by pizza size
- Pizza quantity by category
- Top 5 pizzas by revenue
- Bottom 5 pizzas by revenue

### Data Preparation

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Date and time formatting

Additional time-based features were created from the order date and time, including:

- Order day
- Order month
- Month number
- Order hour

---

## 💡 Key Insights

### 1. Classic is the highest-revenue category

Classic pizzas generated **$220,053.10**, representing **26.91% of total revenue**.

### 2. Large pizzas dominate sales

Large pizzas accounted for approximately **45.89% of total revenue**, making them the strongest-performing size.

### 3. Friday is the strongest sales day

Friday generated **$129,690.90**, the highest revenue among the days of the week.

### 4. Lunch is the strongest sales period

12 PM was the highest-revenue hour, generating **$111,877.90**.

The 12 PM–1 PM period alone contributed approximately **26.65% of total revenue**.

### 5. Thai Chicken Pizza leads by revenue

The Thai Chicken Pizza generated **$43,434.25**, making it the highest-revenue pizza in the analysis.

### 6. Low-performing products represent a small share of revenue

The five lowest-revenue pizzas collectively generated approximately **8.78% of total revenue**.

---

## 📌 Business Recommendations

Based on the analysis:

- Prioritize high-performing pizzas in promotional campaigns.
- Maintain sufficient inventory for high-demand Large pizzas.
- Increase staffing and preparation capacity around peak lunch and evening periods.
- Prepare additional inventory and staffing for high-performing days such as Friday.
- Review low-performing pizzas based on demand, pricing, and ingredient costs.
- Consider targeted promotions during lower-performing sales periods.
- Monitor revenue, orders, AOV, and pizzas per order regularly.

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📁 Project Structure

```text
pizza-sales-analysis/
│
├── data/
│   └── raw/
│       └── pizza_sales.csv
│
├── notebooks/
│   └── pizza_sales_analysis.ipynb
│
├── docs/
│   └── Business_Requirements_Document.docx
│
├── reports/
│   └── insights.md
│
├── .gitignore
├── README.md
└── requirements.txt
