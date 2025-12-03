# ADIDAS-SALES-ANALYSIS
“End-to-end Adidas U.S. Sales Analysis using Power BI, Python (Pandas), and SQL. Includes data cleaning, ETL, DAX measures, and interactive dashboards to analyze revenue, profitability, regional trends, sales channels, and product performance with actionable insights.”

––--PROJECT OVERVIEW--––

The goal of this project is to transform raw Adidas sales data into meaningful insights for business decision-making.
The analysis focuses on:

Revenue by product category, region, and sales channel

Profitability and operating margins

Daily and monthly sales trends

Identification of low-margin/low-performing items

Comparative analysis between channels and product lines

This project demonstrates full-stack analytics: Python → SQL → Power BI.


📦 Adidas-Sales-Analysis
 ├── 📄 Adidas Sales Analysis.pbix        # Power BI dashboard
 ├── 📄 Adidas Sales Dataset.csv          # Raw data
 ├── 📁 scripts/
 │    ├── data_cleaning.py               # Pandas cleaning
 │    └── sql_queries.sql                # SQL validation
 ├── 📁 images/                           # Dashboard screenshots
 ├── 📄 README.md                         # Documentation
 └── 📄 insights.pdf                      # Business insights summary

 🧹 Data Cleaning & Preprocessing (Python)

Performed initial cleanup using Pandas to ensure accurate modeling and visualization.

✔ Key Tasks

Removed currency symbols ($) and Indian comma formatting (3,82,500 → 382500)

Converted Total Sales, Operating Profit, and Units Sold to numeric

Parsed date fields

Created new calculated columns (Operating Margin, Month, Year)

Validated row-level accuracy with SQL cross-checks

——————–––––––––––––––——————
📐 Data Modeling (Power BI)

Performed additional transformations in Power Query:

Removed $ and commas

Corrected data types for numeric fields

Created clean Date hierarchy

Built relationships and optimized visuals

Also added calculated tables and DAX measures for deeper insights.

——————–––––––––––––––————————
📊 Dashboard Overview (Power BI)

Your final dashboard includes:
-----
Page 1 – Executive Summary

KPIs (Revenue, Profit, Units Sold, Avg Margin)

Revenue by product

Revenue by sales method

Top regions
-----
Page 2 – Trends & Regions

Monthly revenue trend

Daily spike & drop analysis

Region-wise revenue & profit
-----
Page 3 – Profitability

Operating profit by product

Margin by sales method

Lowest-margin items table
-----
Page 4 – Product Insights

Men’s footwear performance

Women’s category comparison

Avg units sold per day by product
