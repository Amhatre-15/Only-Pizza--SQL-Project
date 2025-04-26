🍕 Pizza Sales SQL Analysis Project
📌 Project Overview
This project is an end-to-end SQL-based analysis of a fictional pizza business using the onlypizza database. The goal is to extract meaningful business insights from order and sales data through structured SQL queries.

🗃️ Dataset Structure
The project uses the following main tables:

pizzas: Contains pizza ID, size, price, and pizza type reference.

pizza_types: Includes pizza names and their categories.

orders: Stores each order's ID, date, and time.

order_details: Links pizzas to orders with quantity details.

🔍 Key Insights & Analysis
Total Orders & Revenue: Calculated total number of orders and total revenue generated.

Most Popular Items: Identified top-ordered pizzas, most common sizes, and categories.

Revenue Drivers: Analyzed which pizza types and categories bring the most revenue.

Time-Based Trends: Explored order patterns by hour and daily averages.

Advanced Analytics:

Cumulative revenue over time using SUM() OVER().

Top pizzas by revenue using RANK().

Revenue share by category with % formatting.

🛠️ Tools & Technologies
SQL (MySQL or compatible engine)

SQL Queries for Data Analysis

Subqueries, Joins, Window Functions, Aggregations

📈 Outcome
This project helped develop a deeper understanding of business-focused data analysis using SQL, including sales performance, customer preferences, and actionable insights for business decision-making.
