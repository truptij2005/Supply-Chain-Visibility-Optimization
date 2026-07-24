# Supply Chain Visibility Optimization – Milestone 2

## Overview

This milestone focuses on analyzing inventory efficiency and delivery performance using Power BI. The dashboard provides actionable insights into product movement, shipping efficiency, and overall supply chain performance to support data-driven business decisions.


# Inventory Turnover Calculation Approach

Inventory turnover measures how efficiently products move through the supply chain.

## Methodology

1. Imported and cleaned the supply chain dataset using Power Query.
2. Created a star schema with Fact and Dimension tables.
3. Calculated Total Sales using the Sales measure.
4. Analyzed product sales frequency to evaluate inventory movement.
5. Used sales volume as an indicator of inventory turnover because inventory balance data was not available in the dataset.

## KPI Used

- Total Sales
- Total Orders
- Quantity Sold
- Sales by Product
- Sales by Category

Higher sales volume indicates higher inventory turnover, while lower sales volume indicates slower inventory movement.

---

# Slow-moving and Fast-moving Inventory Identification Logic

Products were classified according to their sales performance.

## Fast-moving Inventory

Products having

- High sales volume
- High order frequency
- High revenue contribution

These products require regular replenishment to avoid stock-outs.

## Slow-moving Inventory

Products having

- Low sales volume
- Low customer demand
- Low order frequency

These products may occupy warehouse space unnecessarily and increase inventory carrying costs.

The dashboard identifies these products using sales quantity and total revenue comparisons across all products.

---

# Delivery Performance Analysis Methodology

Delivery performance was evaluated using Order Date and Shipping Date.

## Metrics Calculated

- Total Orders
- Average Delivery Days
- Shipping Mode Performance
- Regional Delivery Performance
- Monthly Delivery Trend

## Delivery Time Calculation

Delivery Days = Shipping Date − Order Date

Products with shorter delivery times indicate better logistics performance, while longer delivery durations highlight potential bottlenecks in the supply chain.

The dashboard enables users to compare delivery performance across:

- Regions
- Markets
- Shipping Modes
- Time Periods

---

# Dashboard Features

## Inventory Analytics

- Total Sales KPI
- Product Category Analysis
- Top Selling Products
- Slow-moving Products
- Inventory Distribution

## Delivery Performance

- Average Delivery Time
- Delivery Trend
- Regional Performance
- Shipping Mode Comparison
- Monthly Order Analysis

Interactive slicers allow filtering by:

- Year
- Region
- Category
- Market

---

# Key Insights

- A small number of products generate the majority of sales revenue.
- Several products consistently show low sales, indicating slow-moving inventory.
- Certain regions experience longer delivery times than others.
- Standard shipping is the most frequently used shipping method.
- Seasonal demand patterns influence sales performance.
- Product categories contribute differently to overall revenue.
- Delivery efficiency varies across markets.

---
---

# Business Recommendations

- Maintain sufficient stock for fast-moving products to prevent stock-outs.
- Reduce procurement of slow-moving inventory to lower holding costs.
- Improve logistics operations in regions with higher delivery times.
- Monitor inventory performance regularly using turnover metrics.
- Optimize warehouse space by removing obsolete inventory.
- Implement demand forecasting to improve inventory planning.
- Continuously monitor delivery KPIs for operational improvement.

---


