E-Commerce Order Management System
Project Overview
The E-Commerce Order Management System is a MySQL database project designed to manage the main activities of an online store. It stores and organizes information about products, categories, customers, orders, payments, and shipping.
Objectives
- Organize e-commerce data into related tables.
- Maintain relationships using primary keys and foreign keys.
- Add, update, retrieve, and delete records using SQL.
- Generate useful summaries about orders, products, customers, and revenue.
Database Tables
- Categories — product category details
- Products — product names, prices, stock, and sales information
- Customers — customer contact and registration details
- Orders — order dates, amounts, and order statuses
- Order_Items — products and quantities included in orders
- Payments — payment methods and payment statuses
- Shipping — shipping and delivery details
SQL Concepts Covered
This project demonstrates:
- Database and table creation
- Primary keys and foreign keys
- CRUD operations (INSERT, UPDATE, DELETE)
- Filtering with WHERE, HAVING, and LIMIT
- Operators such as AND, OR, and NOT
- Sorting and grouping with ORDER BY and GROUP BY
- Aggregate functions such as SUM, AVG, MAX, MIN, and COUNT
- INNER JOIN, LEFT JOIN, RIGHT JOIN, and a UNION-based FULL OUTER JOIN equivalent
- Subqueries
- Date and string functions
- Window functions and CASE expressions
How to Run
1. Open MySQL Workbench.
2. Open the ecommerce_management.sql file.
3. Execute the script to create the database, tables, sample records, and queries.
4. Run the SELECT queries to view the results.
Project Files
- ecommerce_management.sql — SQL database setup, sample data, and queries.
- ecommerce_mysql_outputs_with_reasons.txt — expected outputs and explanations for the queries.
Requirements
- MySQL 8.0 or newer is recommended, as the project uses CTEs and window functions.
Note
Some query results may vary depending on the current date and the order in which statements are executed. The delete operation for old cancelled orders may be blocked by foreign-key constraints while related records still exist.
