📊 Task 6: Sales Trend Analysis Using Aggregations


🎯 Objective
Analyze monthly revenue and order volume from the online_sales dataset using SQL aggregation techniques.


🧰 Tools Used

SQL (Tested on: PostgreSQL, MySQL, and SQLite)


📂 Dataset

Table: orders

Relevant Columns:

order_date – the date of the order

amount – the total value of the order

product_id – the product involved in the order

order_id – the unique ID for each order


📜 Task Description

Write SQL queries to analyze:

Total monthly revenue (sum of amount)

Total order volume (distinct count of order_id)


🧠 SQL Techniques Used

EXTRACT(MONTH FROM order_date) to get the month

EXTRACT(YEAR FROM order_date) to get the year

SUM(amount) to calculate total monthly revenue

COUNT(DISTINCT order_id) to calculate order volume

GROUP BY year and month to aggregate data

ORDER BY to sort by date

LIMIT to focus on specific time periods (e.g., top months)


✅ Outcome

You will learn how to:

Aggregate data over time using SQL

Understand sales trends by month

Extract meaningful insights from raw sales data


📈 Sample Output Format

Year	Month	Total Revenue	Total Orders
2023	1	$12,000.00	150
2023	2	$10,800.00	132
...	...	...	...


📁 Files Included

online_retail_orders.sql: SQL script to perform the analysis

orders.csv: Sample results table (optional export)
