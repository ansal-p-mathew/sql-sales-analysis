-- =====================================
-- PIZZA SALES ANALYSIS PROJECT
-- =====================================

-- BUSINESS PROBLEM:
-- Analyze pizza sales data to identify trends,
-- top products, and revenue drivers

-- =====================================
-- 1. TOTAL ORDERS
-- =====================================
SELECT COUNT(DISTINCT order_id) AS total_orders
FROM orders;

-- =====================================
-- 2. TOTAL REVENUE
-- =====================================
SELECT SUM(od.quantity * p.price) AS total_revenue
FROM order_details od
JOIN pizzas p ON od.pizza_id = p.pizza_id;

-- Continue all your queries...
