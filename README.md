# 🛒 E-Commerce Management System (MySQL)

## 📌 Project Overview

The **E-Commerce Management System** is a MySQL-based database project designed to manage an online shopping platform.

This project helps manage customers, product categories, products, orders, order items, payments, and shipping details.

It demonstrates how SQL queries can be used to store, manage, retrieve, update, and analyze e-commerce data efficiently.

## 🎯 Project Objectives

- Manage customer information.
- Store product and category details.
- Manage customer orders.
- Track order items and quantities.
- Maintain payment information.
- Track shipping and delivery status.
- Generate sales and revenue reports.
- Analyze customer purchasing behavior.

## 🗄️ Database Information

**Database Name:** `ecommerce_db`

### Tables Used

This project contains 7 tables:

| No. | Table Name | Description |
|---|---|---|
| 1 | customers | Stores customer details |
| 2 | categories | Stores product categories |
| 3 | products | Stores product information |
| 4 | orders | Stores customer orders |
| 5 | order_items | Stores ordered product details |
| 6 | payments | Stores payment information |
| 7 | shipping | Stores shipping details |

## 🛠️ Technologies Used

- MySQL
- SQL
- MySQL Workbench

## 📚 SQL Concepts Used

The following SQL concepts are implemented in this project:

### 1. Database Operations
- CREATE DATABASE
- USE DATABASE
- CREATE TABLE

### 2. Data Manipulation Language (DML)
- INSERT
- UPDATE
- DELETE

### 3. Data Query Language (DQL)
- SELECT
- WHERE
- DISTINCT
- ORDER BY
- LIMIT

### 4. Aggregate Functions
- COUNT()
- SUM()
- AVG()
- MIN()
- MAX()

### 5. Grouping
- GROUP BY
- HAVING

### 6. Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN

### 7. Subqueries
- Nested SELECT queries
- NOT IN

### 8. Date Functions
- CURDATE()
- DATE_SUB()
- DATEDIFF()
- MONTH()
- DATE_FORMAT()

### 9. String Functions
- UPPER()
- TRIM()

### 10. Window Functions
- RANK()
- OVER()
- COUNT() OVER()
- SUM() OVER()

### 11. Conditional Statements
- CASE WHEN
- BETWEEN

## 📊 Project Features

- Customer management
- Product and category management
- Order tracking
- Payment status management
- Shipping status management
- Top 5 most purchased products
- Highest spending customer
- Monthly revenue analysis
- Average order value calculation
- Customer loyalty classification (Gold, Silver, Bronze)
- Product sales classification (Best Seller, Popular, Regular)
- Cumulative revenue calculation
- Running order count

## 🔗 Table Relationships

- One category can have multiple products.
- One customer can place multiple orders.
- One order can contain multiple order items.
- One product can appear in multiple order items.
- One order can have payment details.
- One order can have shipping details.

## ▶️ How to Run the Project
