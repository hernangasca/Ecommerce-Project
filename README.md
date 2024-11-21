# Ecommerce Sales Dashboard

This repository contains a data analysis and visualization project developed in Power BI for an e-commerce company. The purpose of the project is to create an interactive dashboard that provides key insights into Year-to-Date (YTD) sales and supports strategic decision-making.

## Overview

![image](https://github.com/user-attachments/assets/23f571eb-8072-469a-8a43-ba90466775ad)


## 🚀 Project Features

### Power BI Functionalities Used
- **Data Integration:** Connected Power BI to MS SQL Server and flat files.
- **Data Modeling:** Created relationships between three tables.
- **Data Cleaning:** Used Power Query to prepare the data.
- **Date Table:** Generated a date table for time-series analysis.
- **Time Intelligence Functions:** Implemented DAX functions such as `TOTALYTD`, `SAMEPERIODLASTYEAR`, etc.
- **Dynamic and Complex KPIs:** Developed customized metrics.
- **Advanced DAX Queries:** Used functions like `CALCULATE`, `SUMX`, `FILTER`, and others.
- **Conditional Formatting:** Added dynamic icons to highlight trends.
- **Insights Generation:** Created charts and visuals for analytical insights.

---

## 📝 Problem Statement

A U.S.-based e-commerce company requested the development of a dashboard to analyze YTD sales data and generate actionable insights. The client requirements included:

1. **Main KPIs:**
   - YTD Sales, YTD Profit, YTD Quantity Sold, and YTD Profit Margin.
   - Year-over-Year (YoY) growth with trend visualizations using sparklines.
2. **Category Analysis:**
   - YTD Sales, PYTD Sales, and YoY growth by customer category with trend icons.
3. **Regional Analysis:**
   - Sales performance by state and region.
   - Identify best- and worst-performing regions.
4. **Product Analysis:**
   - Top 5 and Bottom 5 products based on YTD Sales.
5. **Shipping Analysis:**
   - Sales percentages by shipping method.

---

## 📊 Screenshots

### KPI Banner

![image](https://github.com/user-attachments/assets/c9165e89-4f21-4803-9f34-469e47ae0716)

### Sales by Category

![image](https://github.com/user-attachments/assets/de6e5152-c3d6-416f-8da0-83bba33962a7)


### Sales by Region
![image](https://github.com/user-attachments/assets/7e68b6a3-216a-47a3-b715-23f699b981e8)


### Top and Bottom Products
![image](https://github.com/user-attachments/assets/c5aa118f-f8d0-4ea9-924e-87afb48552e7)

---

## 🛠️ Tools and Technologies

- **Power BI:** For data visualization.
- **Power Query:** For data cleaning and transformation.
- **DAX (Data Analysis Expressions):** For creating measures and custom calculations.
- **SQL:** For extracting data from an MS SQL Server database.

---

## 📂 Project Structure

```plaintext
├── Dataset/
│   ├── sales_data.csv
│   ├── regions.xlsx
├── PowerBI_File/
│   ├── Ecommerce_Dashboard.pbix
├── README.md
