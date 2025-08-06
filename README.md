# 👗 European Fashion Store Dashboard (Databricks)

An interactive Databricks dashboard built for analyzing sales, customer behavior, product performance, and marketing campaign insights for a European Fashion Store. This dashboard uses SQL, data visualization tools, and calculated metrics to support data-driven decision-making.

---

## 📊 Project Overview

This project focuses on building a comprehensive **Databricks dashboard** to monitor the performance of a fashion retail business. It includes **counter visualizations**, **bar/line/pie/area/geo charts**, and **custom metrics** to highlight business KPIs across four main pages:

- **Sales Overview**
- **Sales Details**
- **Product Insights**
- **Customer Analysis**
- **Metric Exploration**

---

## 📁 Dashboard Structure and Visualizations

### 🧾 Overview Page
- **📌 Counter KPIs**:
  - ✅ Total Sales
  - ✅ Total Quantity Sold
  - ✅ Monthly Target Sales (calculated using average product sales per month)
  - ✅ Total Number of Customers
- **📈 Charts**:
  - 📅 Weekly Sales Trend
  - 📦 Quantity Sold per Month
  - 📢 Sales Performed Through Each Channel
  - 📉 Percentage of Discounted Items per Category

---

### 💰 Sales Page
- **📊 Visualizations**:
  - 📊 Sales by Channel Campaign
  - 🔻 Sales by Discount Rate
  - 🛍️ Average Discount by Product Category
  - 📆 Sales by Category and Month
  - 🗺️ Sales Distribution by Country (Geo Map)

---

### 📦 Product Page
- **🏆 Top Insights**:
  - 🔝 Top-Selling Products
  - 💹 Profit Margin by Product
  - 🎯 Sales by Product Category
  - 📏 Sales by Product Size
  - 📈 Quantity Sold vs Stock Level of Each Product

---

### 👥 Customer Page
- **👨‍👩‍👧‍👦 Customer Insights**:
  - 🌍 Sales per Customer Country
  - 🗓️ Customer Signups per Month
  - 👶 Sales per Age Range
  - 🧑‍💼 Customer Type Distribution (New vs Returning)
  - 💸 Average Order Value per Customer

---

### 📐 Metrics Page
- **📊 In-depth Metrics**:
  - 📏 Category-wise Sales from Each Size
  - 📅 Category-wise Sales per Month
  - 📣 Category-wise Quantity Sold via Each Channel

---
## 🧮 Calculation Logic

- **Target Sales**:
  ```sql
  AVG(Monthly Sales for each Product)
  This metric is calculated using window functions to find the average monthly sales per product.

  Profit Margin:
    (Sales - Cost) / Sales

  Average Order Value:
    Total Sales / Number of Orders per Customer

  Discount %:
    (Original Price - Sale Price) / Original Price
##🛠️ Tools and Technologies Used
  Databricks SQL
  Delta Tables
  Databricks Dashboards
  Visualization Types: Counter, Bar, Line, Pie, Area, Geo Map, Table

##🚀 How to Run This Project
  Import all the dataset tables into your Databricks workspace.
  Use SQL to transform data into clean and usable format.
  Create Delta Tables as necessary.
  Build visualizations from SQL queries in the dashboard editor.
  Organize dashboards into four pages: Sales Overview, Sales, Product, Customer, and Metrics.

##📈 Business Outcomes
  Enables the marketing, sales, and inventory teams to track KPIs in real-time.
  Supports campaign performance analysis and stock-level decision making.
  Highlights sales drivers and customer buying behavior effectively.

##📫 Contact
  If you have questions, feedback, or want to collaborate:

  LinkedIn: linkedin.com/in/nilakantha-sahoo2002
  
  Email: snilakantha2002@gmail.com

##⭐ Star this Repo
  If this dashboard inspired you or helped in your learning, please consider giving it a ⭐ on GitHub! 