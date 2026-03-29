# Evaluating-Annual-Sales-Performance-and-Revenue-Drivers-for-Vertex-Electronics
An Excel capstone project analyzing Vertex Electronics' 2025 sales performance. Built an interactive dashboard using Power Pivot, DAX measures, Timeline and Category slicers to track revenue, MOM% trends, regional contribution, product performance, and discount impact.
## Overview

This analysis evaluates the 2025 sales performance of Vertex Electronics, focusing on revenue, impact of discounts, product performance, and customer purchasing patterns. The objective was to identify key revenue drivers, top-performing products and regions, and patterns in customer behavior that affected profitability during 2025.

The findings highlight top-performing products, monthly revenue trends, regional performance patterns, category contributions, the relationship between quantity and revenue, and how discounts influenced sales performance. These historical insights provide guidance for optimizing pricing strategies, product offerings, and overall revenue growth in 2026.

---

## Data Source

The data used for this analysis was obtained from a simulated retail sales dataset for Vertex Electronics, covering transactions over a one-year period (2025).

The dataset includes the following columns:

| Column | Description |
|--------|-------------|
| Order ID | Unique identifier for each transaction |
| Order Date | Date the order was placed |
| Month Name | Month in which the order occurred |
| Customer ID | Unique identifier for each customer |
| Region | Customer's geographical location |
| Product Category | Type or category of the product |
| Product Name | Specific product purchased |
| Quantity | Number of units purchased |
| Unit Price | Price per single unit of the product |
| Total Sales (Before Discount) | Total value of the order before discounts |
| Discount | Discount applied to the order |
| Revenue After Discount | Actual revenue earned after discounts |
| Payment Method | Method used to make the payment |

---

## Problem Statement

Vertex Electronics operated in a competitive retail environment in 2025. While detailed transaction-level sales data exists, there was limited visibility into how product performance, regional demand, pricing strategies, and order quantities influenced overall revenue during that year.

Historical insights are needed to help the business adjust its strategy for 2026 by understanding which products, regions, and strategies were most effective. Without this understanding, it would be difficult to make informed decisions on product assortment, pricing, and revenue optimization.

### Specific Business Problems Being Addressed

- Analyzing monthly sales trends in 2025 to identify patterns, seasonality, and performance fluctuations
- Identifying top-performing products and categories in 2025 that drove the majority of revenue
- Evaluating regional sales performance to determine historically high- and low-performing markets
- Assessing the impact of discounts on revenue and sales during 2025
- Understanding how order quantity influenced revenue generation
- Identifying opportunities to optimize product offerings, pricing strategies, and revenue growth for 2026

### Success Criteria

The analysis aims to generate actionable insights that will:

- Highlight key revenue drivers across products, regions, and time periods in 2025
- Identify top-performing products and categories for strategic focus in 2026
- Evaluate the effectiveness of discount strategies on sales performance
- Provide insights into customer purchasing patterns and order behavior
- Support data-driven decision-making for product strategy, pricing, and revenue optimization in 2026

---

## Tools and Methodology

### Tools

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Dashboard creation, pivot tables, and visualization |
| Power Query | Data cleaning and transformation |
| Power Pivot | Writing DAX measures for key metrics |
| SQL (PostgreSQL) | Queried the dataset to analyze revenue, product performance, regional trends, and discount impact |

### Methodology

**Data Cleaning:** Inspected the sales dataset for inconsistencies, duplicates, and missing values. The original dataset contained 1,250 records across 13 columns. During the data cleaning process, 50 duplicate records were identified and removed. Additionally, 194 records with missing values in key fields (Quantity and Total Sales) were excluded to ensure data accuracy and consistency. This resulted in a final dataset of 1,006 cleaned records used for analysis.

**Data Processing:** Used SQL queries, Excel pivot tables, and DAX measures in Power Pivot to calculate key metrics such as MOM%, total revenue, revenue after discount, average order value, and product/category contributions.

**Sales Analysis:** Analyzed monthly revenue trends, product performance, regional sales patterns, and the impact of order quantity and discounts on revenue to identify key revenue drivers.

**Data Visualization:** Built an interactive Excel dashboard to display key metrics, revenue trends, product performance, regional insights, and discount impacts, providing actionable insights for optimizing 2026 strategies.

---

## Dashboard Overview

The dashboard presents a comprehensive view of Vertex Electronics' 2025 sales performance, highlighting revenue trends, product performance, regional insights, and the impact of discounts on profitability. It illustrates how order size influences revenue and identifies patterns that can guide pricing and product strategy decisions for 2026.

![Dashboard Preview](https://github.com/JonathanHappiness/Evaluating-Annual-Sales-Performance-and-Revenue-Drivers-for-Vertex-Electronics/blob/main/Sales_Dashboard.png?raw=true)

📊 [Click here to interact with the Dashboard](https://1drv.ms/x/c/c0a6ca2a1ad92f49/IQAUQqqozePaS4rk8geNNLY4AbdqdtETppQ5whS3c5psptg)


*Analysis by Jonathan | 2025 Vertex Electronics Sales Performance Project*
