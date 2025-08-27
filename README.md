# Retail-Sales-Analysis-Project-
 "A data analysis project using SQL to analyze retail sales, providing key insights on customer behavior and product performance

 Project Overview
This project focuses on a comprehensive analysis of a retail company's sales data to uncover key business insights and inform strategic decision-making. The analysis was conducted using SQL, demonstrating skills in data manipulation, aggregation, segmentation, and reporting.
The goal was to transform raw transactional data into actionable intelligence by creating a series of analytical queries and two key reporting tables (gold.report_customers and gold.report_products).

 Data Sources
The analysis was performed on three primary datasets:

gold.dim_customers.csv
gold.dim_products.csv
gold.fact_sales.csv


Analysis & Methodology
The analysis was executed in SQL and structured around several key analytical frameworks:

Magnitude Analysis: Queries were run to understand the size and distribution of data, such as finding the total number of customers by country and gender, and total revenue by product category.

Ranking Analysis: Identified top- and bottom-performing entities by revenue and orders. Used both simple TOP clauses and advanced RANK() window functions to rank the best-selling products and top-spending customers.

Change Over Time Analysis: Explored sales trends over time to identify seasonality and growth. Analyzed monthly and yearly sales performance using date functions and LAG() to calculate month-over-month and year-over-year growth.

Data Segmentation: Segmented the data into meaningful groups for targeted insights. Customers were segmented into VIP, Regular, and New tiers based on their total spending and order history. Products were segmented into High-Performer, Mid-Range, and Low-Performer categories based on total sales.

Reporting: The final step was to consolidate all key metrics into two dedicated reporting views (gold.report_customers and gold.report_products). These views were exported as CSV files to create clean, summarized datasets ready for business intelligence tools like Tableau or Power BI.

📈 Key Findings
The project provided a clear view of the business, including:

Identification of high-performing products that contribute the most to overall revenue.

A clear breakdown of customer segments, which can be used for targeted marketing and loyalty campaigns.

The ability to track and measure monthly sales trends and growth rates, allowing the business to anticipate seasonal changes and evaluate performance.

A ready-to-use dataset for further analysis and visualization.

📋 Repository Contents
This repository contains the following files:

SQLQuery1.sql: The complete SQL script containing all the queries used for the analysis, from initial exploration to final reporting.

gold.dim_customers.csv: The raw customer data.

gold.dim_products.csv: The raw product data.

gold.fact_sales.csv: The raw sales data.

gold.report_customers.csv: The final aggregated report on customer metrics.

gold.report_products.csv: The final aggregated report on product metrics.

README.md: This document.
