# Milestone 4 – Warehouse Efficiency and Executive Dashboard

## Project Overview

This milestone focuses on developing the Warehouse Efficiency Dashboard and Executive Dashboard as part of the Supply Chain Visibility & Optimization project.

The dashboards were developed using Microsoft Power BI to analyze warehouse operations, inventory efficiency, warehouse productivity, throughput, and overall supply chain performance.

## Warehouse Utilization Calculation Methodology

Warehouse utilization is used to evaluate how efficiently warehouse capacity is being utilized.

The utilization percentage is calculated as:

**Warehouse Utilization % = Used Capacity / Total Capacity × 100**

The dashboard provides warehouse-level analysis to identify warehouses with high, low, or optimal utilization.

## Throughput and Productivity KPI Calculations

Warehouse throughput measures the quantity or number of orders processed by a warehouse during a selected period.

The throughput analysis is based on:

**Throughput = Total Quantity Processed / Selected Time Period**

Warehouse productivity evaluates operational efficiency using metrics such as order volume, quantity processed, throughput, and delivery performance.

The KPIs are analyzed by warehouse, region, product category, and time period to identify high-performing and underperforming warehouse operations.

## Executive Dashboard Design Methodology

The Executive Dashboard provides a consolidated view of the most important supply chain KPIs from the previous modules.

The dashboard includes key metrics such as:

* Total Sales
* Total Orders
* Total Inventory
* Inventory Turnover
* Average Delivery Days
* On-Time Delivery Percentage
* Warehouse Utilization
* Warehouse Throughput

Interactive slicers are provided for relevant dimensions such as Order Date, Warehouse, Region, and Product Category.

The dashboard uses KPI cards, charts, trend analysis, and comparative visualizations to provide an executive-level overview of supply chain performance.

## Forecasting Implementation Approach

Forecasting is implemented using Power BI time-series forecasting functionality.

Historical data is visualized using line charts based on relevant business metrics such as sales, orders, inventory, or throughput.

The forecast helps identify potential future trends and supports:

* Inventory planning
* Warehouse capacity planning
* Demand planning
* Operational decision-making

## Dashboard Optimization Techniques

The following techniques were considered to improve Power BI report performance and usability:

* Removed unnecessary columns from the dataset.
* Used an appropriate data model and relationships.
* Created reusable DAX measures.
* Minimized unnecessary calculated columns.
* Avoided unnecessary and excessive visuals.
* Used appropriate aggregations.
* Limited high-cardinality fields in visualizations.
* Used slicers only for relevant filtering requirements.
* Reviewed report performance using Power BI Performance Analyzer.
* Designed the dashboard with a clear and consistent layout.

## Key Insights

The dashboards provide insights into:

* Warehouse utilization and operational efficiency.
* Warehouse throughput and productivity.
* Inventory levels across warehouses and regions.
* Inventory performance across product categories.
* Delivery performance across warehouse locations.
* Trends in sales, orders, inventory, and warehouse activity.
* Differences in performance between warehouses.
* Potential areas of excess, slow-moving, or inefficient inventory.

## Business Recommendations

Based on the dashboard analysis, the following recommendations can support supply chain improvement:

* Improve capacity allocation between warehouses.
* Monitor warehouses with low or excessive utilization.
* Improve throughput at underperforming warehouses.
* Reduce excess and dead stock.
* Improve inventory turnover through better inventory planning.
* Monitor slow-moving product categories.
* Improve delivery performance in underperforming regions or warehouses.
* Use historical trends and forecasts for inventory and warehouse capacity planning.
* Continuously monitor warehouse KPIs through the executive dashboard.

## Repository Structure

```text
Supply_Chain_Visibility_Optimization/
└── Milestone 4/
    ├── Milestone4_PowerBI.pbix
    ├── screenshots/
    │   ├── Warehouse_Efficiency.png
    │   └── Executive_Dashboard.png
    └── README.md
```

## Tools and Technologies

* Microsoft Power BI
* DAX
* Power Query
* Data Modeling
* Power BI Forecasting
* GitHub

## Deliverables

* Warehouse Efficiency Dashboard
* Executive Dashboard
* Required DAX Measures and KPIs
* Interactive Filters
* Drill-through Analysis
* Trend Analysis
* Forecasting
* Dashboard Performance Optimization
* Warehouse Efficiency Screenshot
* Executive Dashboard Screenshot
* Power BI PBIX File

