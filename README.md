# Olist E-Commerce Analytics Dashboard

An end-to-end analytics project on the Olist Brazilian e-commerce dataset. Raw CSVs were loaded into PostgreSQL, modeled across related tables (orders, order items, payments, reviews, customers, products), and visualized in a 4-page Power BI report built with DAX measures.

**Scope:** about 99K orders and 96K customers from September 2016 to October 2018, with R$13.6M in total sales, R$137.75 average order value, and 113K products sold.

## What the dashboard answers
- **Executive Sales:** How is the business performing? KPIs, monthly sales trend, sales by state, top categories.
- **Product & Order Analysis:** Which categories drive revenue? Category sales, orders, and average price.
- **Customer Analysis:** Do customers come back? Only 3.12% of customers placed more than one order.
- **Logistics & Customer Satisfaction:** Is freight eating margin, and are customers happy? Average freight per order is R$22.82, and about 77% of reviews are positive.

## Key findings
- Health & beauty (R$1.3M), watches & gifts (R$1.2M), and bed/bath/table (R$1.0M) are the top revenue categories.
- 96.88% of customers bought once, so retention is the biggest growth opportunity.
- Repeat customers have a lower AOV (R$124.91) than one-time customers (R$138.62).

## Files
- `DAX Practice -4.pbix`: Power BI report (open in Power BI Desktop)
- `DAX Practice -4.pdf`: PDF export of all 4 dashboard pages

## Tech stack
PostgreSQL (pgAdmin), Power BI Desktop, DAX, Power Query
