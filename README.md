# Elevate_labs_task3

## 📌 Objective

The objective of this task was to demonstrate proficiency in SQL by:
- Creating and populating relational tables
- Writing SQL queries to extract business insights
- Applying concepts like JOINS, subqueries, aggregate functions, and CASE statements

---

## 🗂 Dataset Used

A simulated **E-commerce database** containing the following tables:
- `customers`: Customer details
- `orders`: Order transactions
- `orders_details`: Items per order
- `products`: Product catalog

---

## 🧱 SQL Schema

Four main tables were created:

- **Customers**
- **Orders**
- **Order_Details**
- **Products**

Sample data was inserted into each table for query execution.

---

## 📊 SQL Queries Performed

1. **High-value orders**  
   → Retrieve orders with a total amount > $1000 along with customer details.

2. **Total quantity of each product sold**  
   → Aggregate product sales across all orders.

3. **Orders with quantity above average**  
   → Compare individual order quantities with the average.

4. **Count of unique products per order**  
   → Identify variety of products in each order.

5. **Monthly sales trend (2023)**  
   → Total quantity sold per month in 2023.

6. **Filtered monthly trend (2023)**  
   → Same as above, but with threshold filter of more than 2 products.

7. **Order classification (High/Low)**  
   → Classify each order based on order amount using `CASE`.

8. **Order classification (3-tier) with filtering**  
   → Classify as High, Medium, Low, and show only ‘High Value’.

---

## 🧠 Concepts Used

- `INNER JOIN`, `GROUP BY`, `ORDER BY`, `HAVING`
- Subqueries
- `CASE` statements for conditional logic
- Date/time functions (`EXTRACT(MONTH/YEAR FROM order_date)`)

---

## 📸 Screenshots

Screenshots of the SQL queries and their outputs are included in the **screenshots/** folder.

---

## 🚀 Tools Used

- **SQLite** for database and SQL execution
- **DB Browser for SQLite** (GUI for execution and screenshots)

---
