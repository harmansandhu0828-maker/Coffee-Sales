# Coffee-Sales
☕ Coffee Sales Analysis Using SQL

📌 Project Overview

This project focuses on analyzing coffee sales data using MySQL to generate meaningful business insights. The project covers sales performance, customer behavior, product popularity, city-wise coffee consumption, monthly sales growth, and market potential.

The database consists of four main tables: Cities, Customers, Products, and Sales.

🛠️ Tools & Technologies

* MySQL
* SQL
* MySQL Workbench
* GitHub

🗄️ Database Schema

The project contains four tables:

Table Name	Description
Cities	Stores city names, population, and average rent
Customers	Stores customer details and city IDs
Products	Stores coffee product names and prices
Sales	Stores sales transactions, dates, quantities, and prices

🎯 Business Questions & SQL Queries

1. Coffee Consumers Count

How many people in each city are estimated to consume coffee, given that
25% of the population does?

2. Total Revenue from Coffee Sales

What is the total revenue generated from coffee sales across all cities in the
last quarter of 2023?

3. Sales Count for Each Product

How many units of each coffee product have been sold?

4. Average Sales Amount per City

What is the average sales amount per customer in each city?

5. City Population and Coffee Consumers

Provide a list of cities along with their populations and estimated coffee
consumers.

6. Top Selling Products by City

What are the top 3 selling products in each city based on sales volume?

7. Customer Segmentation by City

How many unique customers are there in each city who have purchased
coffee products?

8. Average Sale vs Rent

Find each city and their average sale per customer and avg rent per customer

9. Monthly Sales Growth

Sales growth rate: Calculate the percentage growth (or decline) in sales
over different time periods (monthly).

10. Market Potential Analysis

Identify top 3 city based on highest sales, return city name, total sale, total
rent, total customers, estimated coffee consumer

💡 SQL Concepts Used

* Database and Table Creation
* Data Insertion
* SELECT and WHERE
* GROUP BY and ORDER BY
* Aggregate Functions (SUM, COUNT, AVG)
* INNER JOIN and LEFT JOIN
* Common Table Expressions (CTEs)
* Subqueries
* Window Functions (DENSE_RANK, LAG)
* Date Functions
* CASE Statements
* NULLIF and COALESCE
* Revenue and Percentage Calculations

⚙️ How to Run the Project

1. Clone or download this repository.
2. Open MySQL Workbench.
3. Open the coffee_sales_analysis.sql file.
4. Execute the database creation and table creation statements.
5. Insert the sample data into the tables.
6. Execute the SQL queries individually.
7. Analyze the results and business insights.

📁 Project Structure

Coffee-Sales-SQL-Project/
│
├── README.md
├── coffee_sales_analysis.sql
└── LICENSE

📝 Assumptions

* 25% of each city’s population is considered the estimated coffee-consuming population.
* Total revenue is calculated using quantity multiplied by unit price.
* Average sales per customer is calculated using unique purchasing customers.
* Monthly sales growth is calculated using the previous month’s revenue.
* Rent figures are illustrative sample values.
* The project uses sample data for demonstration purposes.

📈 Project Outcomes

This project demonstrates how SQL can be used to solve real-world business problems, analyze sales trends, identify customer patterns, evaluate product performance, and support data-driven business decisions.

👨‍💻 Author

Coffee Sales Analysis | SQL Project

⭐ If you find this project useful, please consider giving this repository a star!

#SQL #MySQL #DataAnalysis #CoffeeSales #DataAnalytics
