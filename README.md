# 🛒 E-Commerce Management System

## 📌 Project Overview

The **E-Commerce Management System** is a MySQL-based database project designed to manage an online shopping platform efficiently.

This project stores and manages information about customers, product categories, products, orders, order items, payments, and shipping details. It demonstrates important SQL concepts such as database creation, table creation, CRUD operations, JOINs, subqueries, aggregate functions, date functions, string functions, and advanced SQL queries.

## 🎯 Project Objectives

- To create and manage an e-commerce database.
- To store customer information.
- To manage product categories and product details.
- To maintain customer orders and order items.
- To manage payment and shipping information.
- To perform INSERT, UPDATE, and DELETE operations.
- To retrieve meaningful information using SQL queries.
- To analyze sales, revenue, and customer purchasing behavior.

## 🛠️ Technologies Used

- **Database:** MySQL
- **Language:** SQL
- **Tool:** MySQL Workbench

## 🗂️ Database Structure

**Database Name:** `ecommerce_db`

This project contains seven tables:

| Table Name | Description |
|---|---|
| customers | Stores customer details such as name, email, phone number, address, and registration date. |
| categories | Stores product category information. |
| products | Stores product names, prices, stock quantities, and category references. |
| orders | Stores customer order details, order dates, amounts, and statuses. |
| order_items | Stores products included in each order, quantities, and subtotals. |
| payments | Stores payment dates, payment methods, and payment statuses. |
| shipping | Stores shipping dates, delivery dates, and shipping statuses. |

## 🔗 Table Relationships

- Customers → Orders (One-to-Many)
- Categories → Products (One-to-Many)
- Orders → Order_Items (One-to-Many)
- Products → Order_Items (One-to-Many)
- Orders → Payments (One-to-Many)
- Orders → Shipping (One-to-Many)

**Foreign Key Relationships:**

- `products.category_id` references `categories.category_id`.
- `orders.customer_id` references `customers.customer_id`.
- `order_items.order_id` references `orders.order_id`.
- `order_items.product_id` references `products.product_id`.
- `payments.order_id` references `orders.order_id`.
- `shipping.order_id` references `orders.order_id`.

## 📚 SQL Concepts Covered

### 1. Database and Table Operations
- CREATE DATABASE IF NOT EXISTS
- USE
- CREATE TABLE

### 2. Data Manipulation Language (DML)
- INSERT
- UPDATE
- DELETE (Foreign Key CASCADE behavior)

### 3. Data Query Language (DQL)
- SELECT
- WHERE
- DISTINCT
- ORDER BY
- LIMIT
- IN

### 4. SQL JOIN Operations
- INNER JOIN
- LEFT JOIN
- Multiple Table JOIN
- JOIN with multiple conditions
- LEFT JOIN with NULL checking

### 5. Aggregate Functions
- COUNT()
- SUM()
- AVG()

### 6. Grouping and Filtering
- GROUP BY
- HAVING

### 7. Subqueries
- Subqueries with IN
- NOT IN
- Subqueries for finding products never ordered

### 8. Date and Time Functions
- CURDATE()
- DATE_SUB()
- MONTH()
- DATEDIFF()
- DATE_FORMAT()

### 9. String Functions
- UPPER()
- TRIM()

### 10. Advanced SQL Concepts
- CASE Statement
- Window Functions
- RANK()
- Running Total
- Cumulative Revenue
- Customer Ranking
- Product Categorization
- Customer Loyalty Classification

## ⚙️ Project Features

1. Create and manage customer records.
2. Manage different product categories.
3. Add products with prices and stock quantities.
4. Maintain customer orders and order details.
5. Store payment information and payment statuses.
6. Track shipping and delivery information.
7. Find cancelled orders older than 30 days.
8. Retrieve orders placed in the last one month.
9. Display the top 5 highest-priced products.
10. Find customers with more than 3 orders.
11. Retrieve orders with specific order and payment statuses.
12. Find products that are available in stock.
13. Identify customers registered after a specific date or having purchases above a particular amount.
14. Sort products by price in ascending order.
15. Calculate total orders per customer.
16. Calculate total revenue generated per category.
17. Calculate total store revenue excluding cancelled orders.
18. Find the top 5 most purchased products by quantity.
19. Calculate average order value.
20. Retrieve product and category information using INNER JOIN.
21. Display order and customer information using LEFT JOIN.
22. Identify orders without shipping records.
23. Find customers who have never placed an order.
24. Retrieve customers registered after a specific date with their order details.
25. Identify the customer who spent the most.
26. Find products that have never been ordered.
27. Calculate the total number of orders per month.
28. Calculate delivery days using DATEDIFF().
29. Format order dates using DATE_FORMAT().
30. Update product names using UPPER().
31. Remove extra spaces from customer names using TRIM().
32. Update missing customer email values.
33. Rank customers based on their total spending using RANK().
34. Calculate cumulative monthly revenue using Window Functions.
35. Calculate running totals of orders.
36. Categorize products using CASE statements.
37. Classify customers into Gold, Silver, and Bronze loyalty levels.

## 🚀 How to Run the Project

1. Install MySQL Server and MySQL Workbench.
2. Open MySQL Workbench.
3. Create a new SQL query tab.
4. Copy the complete SQL project code.
5. Execute the SQL script step by step.
6. Check the database and all seven tables.
7. Execute SELECT queries to view the records and results.
8. Verify the JOINs, aggregate functions, subqueries, and advanced SQL queries.

## 📊 Sample Database Information

The project initially contains the following records:

| Table Name | Initial Records |
|---|---:|
| customers | 6 |
| categories | 5 |
| products | 6 |
| orders | 6 |
| order_items | 6 |
| payments | 6 |
| shipping | 6 |

**Total Tables:** 7

**Total Initial Records:** 41

## 💡 Learning Outcomes

Through this project, I learned:

- How to create and manage relational databases.
- How to create tables and establish relationships using Primary Keys and Foreign Keys.
- How to perform INSERT and UPDATE operations.
- How Foreign Key constraints and ON DELETE CASCADE work.
- How to retrieve data using INNER JOIN and LEFT JOIN.
- How to use aggregate functions such as COUNT(), SUM(), and AVG().
- How to apply GROUP BY and HAVING clauses.
- How to write subqueries using IN and NOT IN.
- How to work with SQL date and string functions.
- How to implement CASE statements.
- How to use Window Functions such as RANK().
- How to calculate running totals and cumulative revenue.
- How to analyze customer spending, product sales, and store revenue.

---

**Project Name:** E-Commerce Management System

**Database Name:** ecommerce_db

**Technology:** MySQL

**Project Type:** Database Management System

---

## ⭐ Conclusion

The E-Commerce Management System is a practical MySQL database project that demonstrates essential database management concepts and SQL query-writing skills. It provides hands-on experience with relational database design, customer and product management, order processing, payment tracking, shipping management, JOINs, subqueries, aggregate functions, and advanced SQL concepts such as Window Functions and CASE statements.

This project helped me improve my practical SQL knowledge and understand how relational databases are used to manage an e-commerce platform efficiently.
