# Olist Supply Chain & Sales Performance Dashboard

End-to-end Supply Chain Analytics project using **Python** and **Power BI** on the Brazilian E-Commerce (Olist) dataset.

## Project Overview

This project analyzes 100K+ real e-commerce orders to evaluate sales performance and delivery efficiency. The goal is to provide actionable insights on revenue trends, delivery lead time, on-time performance, and product category contribution.

### Key Objectives
- Clean and prepare raw e-commerce data using Python
- Calculate important Supply Chain KPIs (Lead Time, On-Time Delivery %, Delay Rate)
- Build an interactive Power BI dashboard with 3 pages
- Generate insights and simple revenue forecast

## Tools & Technologies

- **Python** (Pandas, NumPy) – Data Cleaning & Feature Engineering
- **Power BI** – Interactive Dashboard & Visualization
- **DAX** – Measures and KPIs

## Dataset

- Source: [Brazilian E-Commerce Public Dataset by Olist (Kaggle)](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Period: 2016 – 2018
- Approx. 100,000+ orders

## Project Workflow

1. **Data Cleaning & Feature Engineering (Python)**
   - Merged multiple tables (Orders, Items, Products, Customers, Sellers)
   - Created key features:
     - Lead Time
     - Delivery Delay
     - On-Time / Delayed flag
     - Total Order Value
   - Filtered only delivered orders

2. **Power BI Dashboard**
   - Built interactive report with 3 pages
   - Created DAX measures for KPIs
   - Added Month slicer and dynamic insights

## Dashboard Pages

### 1. Executive Overview
- Total Revenue, Total Orders, Avg Lead Time
- On-Time Delivery % and Delayed %
- Monthly Revenue Trend
- Top Product Categories by Revenue
- Quick Insights

### 2. Delivery Performance
- Average Lead Time by Customer State
- Average Lead Time by Product Category
- Delayed Orders by Seller State
- Delivery Delay Distribution

### 3. Insights & Forecast
- Monthly Revenue Forecast
- Revenue by Customer State
- Key Insights & Recommendations

## Key Insights

- Overall On-Time Delivery Rate: **~93%**
- Average Lead Time: **~12 days**
- Top performing category: **Health & Beauty**
- Highest revenue month: **May**
- Lowest revenue month: **September**

## How to Use

1. Download / Clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. (Optional) Run the Python notebook to reproduce the cleaned dataset

## Author

**Shaiful Islam**  
BSc in Economics  
Aspiring Supply Chain / Data Analyst

---

Feel free to star this repository if you find it useful!# E-Commerce-Sales-Dashboard
