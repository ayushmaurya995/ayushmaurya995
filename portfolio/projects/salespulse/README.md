# SalesPulse — Sales Performance Intelligence Dashboard

A lightweight, responsive sales dashboard built to demonstrate practical business analytics without a complicated backend.

## What it shows
- Revenue, profit, units sold and profit margin
- Monthly revenue trend
- Revenue by category and region
- Top products by revenue
- Region and category filters with reset

## Run locally
No build step or installation is required. Open `index.html` in a modern browser. The charts use Chart.js from its public CDN, so an internet connection is needed for chart rendering.

## Data
`data/sales_sample.csv` contains a small **illustrative sample dataset** created for this project. It is not live company data and must not be represented as real business performance.

## Calculations
- Total revenue = sum of revenue
- Total profit = sum of profit
- Units sold = sum of units
- Profit margin = total profit / total revenue × 100

## Files
- `index.html` — complete interactive dashboard
- `data/sales_sample.csv` — sample data
- `assets/dashboard-preview.svg` — dashboard preview artwork

## Tech
HTML · CSS · JavaScript · Chart.js · CSV

## Interview explanation
“SalesPulse is a small business intelligence dashboard. I used a clearly labelled sample sales dataset, calculated core KPIs, and added filters so users can compare regions and product categories. The goal was to make sales performance easy to understand at a glance.”

## Limitations
This is a front-end demonstration using embedded sample records. It has no authentication, database, live sales feed, or predictive model.
