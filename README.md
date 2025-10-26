**Madhav E-Commerce Sales Dashboard — Power BI--**
This repository contains my Power BI project titled Madhav E-Commerce Sales Dashboard, 
created using datasets — Name, Details, and Orders. The purpose of this project is to perform interactive data analysis 
and visualization for understanding sales performance, profit trends, and customer insights in an e-commerce business.

**📊 Project Overview**
This dashboard provides a complete overview of sales and order data from Madhav E-Commerce.
It helps identify key trends, track revenue and profit, analyze product performance, and make data-driven decisions.
**
Objective:** To analyze and visualize e-commerce sales using Power BI to identify top-performing products, profitable regions, and customer behavior patterns.

**🧾 Datasets Used**
The project uses the following datasets:
Name Dataset – Contains basic information about customers or products (e.g., Product Name, Category, Sub-Category, Region).
Details Dataset – Includes transaction-level details such as Product ID, Customer ID, Order ID, and pricing details.
Orders Dataset – Holds order-related information such as Order Date, Ship Date, Quantity, Sales, Profit, and Discount.
Each dataset is connected through key relationships (e.g., Order ID, Product ID, Customer ID) to form a relational model in Power BI.

**⚙️ Data Model and Relationships**
One-to-many relationship between Orders and Details tables.
One-to-one or lookup relationship between Details and Name (depending on structure).
Data cleaning and transformation performed in Power Query Editor to ensure consistency and remove duplicates.
Created calculated columns and DAX measures for metrics such as Total Sales, Profit Margin, and Quantity Sold.

**📈 Key Performance Indicators (KPIs)**
Total Sales – Total revenue generated from all orders.
Total Profit – Net profit across all transactions.
Average Order Value (AOV) – Average revenue per order.
Quantity Sold – Total number of items sold.
Profit Margin % – Ratio of profit to sales.

**📊 Dashboard Features**
Overview Page: Displays total sales, profit, and order summary with slicers for region, category, and date.
Sales Analysis: Monthly and yearly sales trends, YoY comparison, and product-level insights.
Profitability View: Category-wise and subcategory-wise profit margin visualization.
Customer Insights: Top customers and regional contribution.
Interctive Filters: Allow users to explore data by Category, Region, and Time period.

**🧠 Tools and Technologies Used**
Power BI Desktop — for creating the dashboard and visuals.
Power Query — for data cleaning and transformation.
DAX (Data Analysis Expressions) — for calculated columns and custom measures.
CSV Files (Name, Details, Orders) — as data sources

**Repository Structure****
Madhav-Ecommerce-PowerBI/
├─ dataset/
│ ├─ Name.csv
│ ├─ Details.csv
│ └─ Orders.csv
├─ pbix/
│ └─ madhav_ecommerce.pbix
├─ docs/
│ ├─ screenshots/
│ │ ├─ overview_page.png
│ │ └─ sales_analysis.png
│ └─ report_export.pdf
├─ dax/
│ └─ measures.md
├─ README.md
└─ LICENSE

**🚀 Steps to Reproduce**
-Download the repository or clone it:
git clone https://github.com/ayshajindal123/Madhav-Ecommerce-Sales-Dashboard.git
-Open Power BI Desktop.
-Load the datasets (Name.csv, Details.csv, Orders.csv) from the dataset/ folder.
-Open madhav_ecommerce.pbix from the pbix/ folder.
-Refresh data connections if necessary (Home → Transform Data → Data Source Settings → Edit Permissions).
-Explore the visuals and filters to analyze performance metrics.

