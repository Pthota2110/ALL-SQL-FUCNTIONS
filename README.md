# **E-commerce Analytics SQL Pack**

## **Project Overview**
This repository contains a curated set of **SQL queries for E-commerce Analytics**.  
It demonstrates how to analyze customer behavior, sales trends, and product performance  
using **advanced SQL techniques** like CTEs, window functions, and indexes.

## **Key Features**
- Customer order frequency & repeat purchase detection  
- Average Order Value (AOV) per customer  
- Top products by revenue contribution  
- Monthly sales trend analysis  
- Detect duplicate customer emails (data quality check)  
- Lifetime revenue ranking of customers  
- RFM (Recency, Frequency, Monetary) segmentation  
- Works with **Postgres & MySQL**

## **Schema Assumptions**
The queries assume the following tables:
- `customers(customer_id, customer_name, email, created_at)`
- `orders(order_id, customer_id, order_date, order_amount, status)`
- `order_items(order_id, product_id, quantity, unit_price)`
- `products(product_id, product_name, category)`
## **How to Run**
```bash
git clone https://github.com/pthota2110/ecommerce-sql-analytics.git
cd ecommerce-sql-analytics/sql
