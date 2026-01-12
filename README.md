Supply Chain OTIF Performance Analysis – Power BI
 Project Overview

This project analyzes Supply Chain Order Fulfillment Performance using key metrics such as:

OTIF (On-Time In-Full)

OT (On-Time)

IF (In-Full)

Order Line Fill Rate

Customer & City Level Service Performance

The goal is to identify delivery delays, fulfillment gaps, and customer-level service issues so that operations teams can improve logistics efficiency and customer satisfaction.

 Business Problem

Companies often fail to meet delivery targets because:

Orders arrive late

Orders arrive incomplete

High-value customers are not prioritized

Poor visibility across cities and customers

This dashboard helps:

Track service level KPIs

Identify low-performing customers and cities

Compare actual vs target performance

Monitor month-wise trends

 Key KPIs in the Dashboard
Metric	Description
OT%	% of orders delivered on time
IF%	% of orders delivered in full quantity
OTIF%	% of orders delivered on time and in full
OTIF Avg %	Average OTIF across all customers
VOFR%	Volume Order Fill Rate
Total Orders	Total customer orders
Total Order Lines	Number of product lines shipped
📊 Dashboard Features

✔ Executive KPI cards for fast monitoring
✔ Customer-wise OTIF ranking
✔ City-wise performance comparison
✔ Month and week slicers
✔ Goal vs Actual comparison
✔ Alert indicators for under-performance

 Data Model

The data follows a Star Schema:

Dimensions

dim_customers

dim_products

dim_date

dim_targets_orders

Fact Tables

fact_order_lines

fact_orders_aggregate

This enables fast filtering, clean relationships, and scalable reporting.

 Tools & Skills Used

Power BI Desktop

Power Query (Data Cleaning & Transformation)

DAX (Measures & KPIs)

Data Modeling (Star Schema)

KPI & Business Dashboard Design

 Insights from the Dashboard

Overall OTIF = 29.02%, far below the target (65.91%)

On-Time Delivery (59.03%) is much higher than In-Full (52.78%), showing quantity shortages are a major issue

Certain customers have OTIF < 40%, indicating high service risk

Cities like Surat and Ahmedabad show weaker performance compared to others

Performance drops in specific months and weeks, revealing logistics bottlenecks

 Files

supplychain_analysis.pbix – Power BI dashboard

screenshots/ – Dashboard images

 Author

Swapna Jyothi
Data Analyst | Power BI | Data Science

