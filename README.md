# ☕ Coffee Shop Sales Analysis

## 📊 Project Overview
This project analyzes sales data from a coffee shop using **MySQL Server**. The data includes transaction details such as date, time, quantities, prices, product information, and store locations. The goal is to extract meaningful insights through SQL queries and visualize key performance indicators (KPIs).

## 🛠️ Data Cleaning & Preparation
- Converted `transaction_date` and `transaction_time` columns to correct **DATE** and **TIME** formats.
- Identified and corrected **data types** of all columns for accurate calculations.
- Ensured consistency in product and location data.

## 📈 Key Performance Indicators (KPIs) Analyzed
- **Total Sales (Revenue)**
- **Total Orders**
- **Total Quantities Sold**

## 📅 Month-on-Month (MoM) Analysis
- Calculated **MoM difference** and **MoM growth percentage** for:
  - Total Sales
  - Total Orders
  - Total Quantities Sold

## 🕒 Sales Trend Analysis
- **Daily sales trends** over the period.
- Comparison of **weekday vs. weekend sales**.
- **Daily sales vs. average daily sales**.
- Sales breakdown:
  - By **product** and **product category**.
  - By **store location**.
  - By **hour of the day**.
  - By **specific day of a month**.
  - By **hourly sales in a specific month**.

## 🧮 SQL Functions & Techniques Used
- Date and time conversions using **STR_TO_DATE**, **CONVERT**, **CAST**.
- Analytical functions like **LAG()** for MoM comparisons.
- Aggregations with **SUM**, **COUNT**, **ROUND**, **FORMAT**.
- Conditional logic with **CASE WHEN**.
- Grouping and sorting data for trend analysis.

## 🧰 Tools & Technologies
- **MySQL Server** 

## ✅ Insights & Outcome
- Identified peak sales periods by day and hour.
- Recognized best-selling products and high-performing store locations.
- Provided a clear view of sales performance trends over time.
- Delivered actionable insights on daily, weekly, and monthly sales patterns.
