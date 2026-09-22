# Intermediate-Assessment-codeathon
Sales Data Analysis Dashboard

📌 Project Overview

![Sales Dashboard Preview]<img width="1737" height="745" alt="Screenshot 2026-09-22 115536" src="https://github.com/user-attachments/assets/34e66e58-c26e-40fa-9a49-1400310876a7" />


This project presents an interactive Sales Dashboard created using Power BI...

This project focuses on analyzing a sales dataset using Power BI. The dataset was cleaned and prepared using Power Query, followed by data analysis and visualization in Power BI.

The main objective is to understand sales performance, customer behavior, product trends, profitability, and regional order patterns.

📊 Dataset

- Total Records: 1,000
- Tool Used: Power BI
- Data Cleaning: Power Query
- Visualization: Power BI

Columns

Column| Description
Order ID| Unique identifier for each order
Order Date| Date on which the order was placed
Customer Name| Name of the customer
Region| Sales region
Product| Product purchased
Category| Product category
Quantity| Number of units ordered
Unit Price| Price per unit
Sales| Total sales amount
Cost| Cost associated with the order
Profit| Profit generated from the order

🧹 Data Cleaning

The dataset was prepared using Power Query with the following steps:

- Handled missing values in relevant columns.
- Replaced missing categorical values with "Unknown" where appropriate.
- Removed duplicate records based on the unique Order ID.
- Removed rows where Order Date was missing.
- Standardized the Order Date column to a consistent date format.
- Checked numerical columns for missing and inconsistent values.
- Verified the cleaned dataset before loading it into Power BI.

📈 Dashboard Pages

1. Sales Analysis and Overview

This page provides an overall view of sales performance.

Key KPIs:

- Total Sales
- Total Orders
- Total Profit


Visualizations

- Sales by Region
- Order Distribution by Region
- Total Sales by Product
- Total Sales by Year

2. Sales and Profit Analysis

This page focuses on analyzing sales performance and profitability across different categories, regions, products, and time periods.

Key Performance Indicators (KPIs)

- Average Sales
- Average Profit
- Total Quantity
- Profit Margin

Visualizations

- Sales vs Profit by Category
- Total Profit by Region
- Sales vs Profit by Product
- Profit Trend over Time
 
3. Customer and Product Analysis

This page focuses on customer and product performance, helping to identify key customers, popular products, and sales contribution across product categories.

Key Performance Indicators (KPIs)

- Total Customers
- Total Products
- Top Product by Sales
- Top Customer

Visualizations

- Top 5 Customers by Sales
- Top 5 Trending Products by Number of Orders
- Total Sales by Product and Category

  4. Insights and Recommendations

This page summarizes the key findings from the sales analysis and provides recommendations based on the observed sales, profit, customer, and product performance.

Key Performance Indicators (KPIs)

- Total Sales
- Total Profit
- Total Customers
- Total Products

Key Insights

This section highlights the major findings identified from the dashboard analysis, including sales performance, profitability, customer contribution, and product performance.

Recommendations

This section provides actionable recommendations based on the key insights to support better sales performance, profitability, customer engagement, and product-level decisions.

Visualization

- Total Profit by Product

   Power BI Features and DAX Concepts

The dashboard demonstrates various Power BI features and DAX concepts used for interactive analysis and data modeling.

Interactive Features

- Reset Button – Allows users to clear applied filters and return to the default dashboard view.
- Page Navigation – Enables users to navigate easily between different dashboard pages.
- Drill-through – Product Details – Allows users to drill into a selected product and view detailed product-level information.

DAX and Data Modeling

- Calculated Column – Profit Cost Difference – Created to calculate the difference between profit and cost at the row level.
- DAX Measure – Total Profit – Created to calculate the overall profit using DAX.
- Calculated Table – East Region Orders – Created using DAX to separately analyze orders from the East region.
