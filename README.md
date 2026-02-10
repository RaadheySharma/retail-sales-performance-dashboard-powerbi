# 📊 Retail Sales & Performance Dashboard (Power BI)

## Project Overview
This project showcases a comprehensive end-to-end business dashboard developed using Power BI. The dashboard aims to provide a way to track KPIs (Transactions,Revenue,Profit,Returns),compare regional performance across 3 nations (USA,Canada & Mexico) and analyze product level trends to identify top performing products. 

## 🎯 Business Objective
- Monitor revenue, profit, orders, and return rates and present them through KPI Cards 
- Identify top-performing product brands 
- Track global sales performance
- Compare performance against targets
- Adjusted the graphs according to the user’s needs by using parameters based on “Field Parameters” 

---

## 🛠 Tools & Technologies
- Power BI
- DAX (Data Analysis Expressions)
- Data Cleaning & Transformation
- CSV Data Processing
- Data Modeling
- Data Visualization

---

## 📂 Dataset Information
Dataset Used: AdventureWorks Dataset (Maven Analytics) 
Data Source: CSV files  

Data Includes:
- Sales data
- Customer data
- Product information
- Orders and returns
- Region Data 
- Stores Data 

---

## ⚙️ Data Preparation & Modeling
- Imported multiple CSV datasets
- Cleaned and transformed raw data
- Handled missing and inconsistent values
- Created relationships between tables
- Created Calendar Table to create relationship of the calendar table with all the other tables that contains date 
- Created Calculated Columns 
- Created DAX Measure for
  -> Total Orders/Profit/Revenue/Cost/Returns/Customers
  -> Previous Month Revenue/Orders/Profit/Returns (Using "CALCULATE"  with "DATEADD" nested with it)
  -> Year To Date Revenue  
- Created New Parameters of "Fields" named as "Head" to show different charts according to the user's needs (Fields are Total Revenue,Total Profit,Total Transaction,Total Returns and Total Cost)
- Designed KPI metrics to show business performance 
- Presented the Total Customers by Country on Map (3 countries are USA,Canada & Mexico)

---

## 📊 Dashboard Features

### 🔹 Executive Dashboard
- Revenue, Profit, Transactions, Returns KPIs
- Revenue trend analysis
- Monthly Product performance vs Target Gauges for Revenue and Profit 
- Monthly performance tracking through 4 parameters (Revenue,Transaction,Cost and Returns)
- Field Parameters to show graphs according to user's need of Total Revenue,Total Profit,Total Transaction,Total Returns and Total Cost
- Top Performing Product Brand on the basis of Total Orders
- Interactive filters and slicer pane

### 🔹 Geographic Analysis
- Global sales performance of the comapny on the basis of total orders presented through bubbles on the map across 3 Nations (USA,Canada & Mexico)
- Country-Wise filtering (USA,Canada & Mexico)

---

## 📈 Key Insights
- Total Revenue generated of $1.76 Million
- Total Profit of $ 1 Million 
- Total Transactions of 2,70,000
- Return Rate of .99% 
- Total Returns of 7000
- Revenue of the company was highest on 4 Decemeber 1998, amounted to $1,20,160
- On December 4, 1998, the company reached its highest revenue to date, surpassing both revenue and profit targets. However, it was unable to reduce returns, as the monthly returns exceeded the target.
- United States is the country from where most of the order were placed

---

## 🖼 Dashboard Screenshots
![Dashboard Preview](https://github.com/RaadheySharma/retail-sales-performance-dashboard-powerbi/blob/main/Dashboard%20Maven%20Market.png)
![Map](https://github.com/RaadheySharma/retail-sales-performance-dashboard-powerbi/blob/main/Map.png)
---
