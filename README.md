# SQL Pizza Sales Analysis

## Project Overview

This project analyzes a pizza sales dataset using SQL to uncover key business insights related to revenue, customer ordering behavior, and product performance. The goal is to simulate a real-world business scenario and derive actionable insights from structured data.

---

## Tools & Technologies

* SQL (MySQL)
* GitHub

---

## Dataset Description

The dataset consists of four relational tables:

* **orders**: Contains order date and time information
* **order_details**: Contains pizza quantity and order mapping
* **pizzas**: Contains pizza size and pricing details
* **pizza_types**: Contains pizza names, categories, and ingredients

---

## Data Model

The tables are related as follows:

orders → order_details → pizzas → pizza_types

This structure enables multi-level analysis using joins.

---

## Business Objectives

* Calculate total revenue and number of orders
* Identify top-selling and highest revenue-generating pizzas
* Analyze sales distribution across categories and sizes
* Determine peak order times and trends
* Evaluate product performance for business decisions

---

##  Key Analysis Performed

### Basic Analysis

* Total number of orders
* Total revenue generated

### Product Analysis

* Top 5 most ordered pizzas
* Highest priced pizzas
* Most popular pizza sizes

### Sales Analysis

* Revenue by pizza category
* Daily and hourly order trends

### Advanced Analysis

* Ranking pizzas based on revenue using window functions
* Identifying high-performing vs low-performing products

---

## Key Insights

* **Classic category** contributes the highest share of total revenue
* **Large-sized pizzas** are the most frequently ordered
* **Evening hours (6 PM – 8 PM)** show peak order activity
* A small group of pizzas contributes significantly to overall revenue (Pareto effect)
* Certain pizzas show consistently low performance and may need review

---


## To Run the Project

1. Import the CSV files into your SQL database
2. Create tables based on dataset structure
3. Run queries from `pizza_sales_analysis.sql`
4. Analyze results and derive insights

---
