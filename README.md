# E-Commerce Sales Analysis

## Project Overview

This project performs exploratory data analysis on the Brazilian E-Commerce Public Dataset by Olist.

The objective is to analyze sales performance, customer behavior, product categories, payment preferences, regional performance, reviews, and delivery trends using Python.

## Objectives

- Analyze overall e-commerce sales performance.
- Identify high-performing product categories.
- Analyze monthly order trends.
- Identify the highest-revenue regions.
- Understand customer payment preferences.
- Analyze customer review scores.
- Compare product prices with freight costs.
- Identify high-demand product categories.
- Analyze order status distribution.
- Analyze delivery performance.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses the Brazilian E-Commerce Public Dataset by Olist.

The dataset contains information about:

- Orders
- Customers
- Products
- Order Items
- Payments
- Reviews

## Analysis Performed

### 1. Revenue by Product Category
Identifies the product categories generating the highest revenue.

### 2. Monthly Order Trend
Analyzes order volume across different months.

### 3. Regional Revenue
Identifies the highest-performing customer regions.

### 4. Payment Methods
Analyzes the payment methods most frequently used by customers.

### 5. Customer Reviews
Analyzes the distribution and average of customer review scores.

### 6. Product Price vs Freight
Compares product prices with associated freight costs.

### 7. Product Category Demand
Identifies categories with the highest number of items sold.

### 8. Order Status
Analyzes the distribution of different order statuses.

### 9. Delivery Performance
Analyzes the time taken to deliver orders to customers.

## Project Structure

```text
Ecommerce_Sales/
│
├── charts/
│   ├── revenue_by_category.png
│   ├── monthly_order_trend.png
│   ├── revenue_by_region.png
│   ├── payment_methods.png
│   ├── review_score_distribution.png
│   ├── price_vs_freight.png
│   ├── top_categories_by_orders.png
│   ├── order_status_distribution.png
│   └── delivery_time_distribution.png
│
├── data/
│   ├── olist_orders_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_products_dataset.csv
│   └── olist_customers_dataset.csv
│
├── .venv/
│
├── ecommerce_sales_analysis.ipynb
│
└── README.md