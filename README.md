# SalesDashboard-Tableau

A Tableau dashboard built to explore sales trends, regional performance, and profitability across Indian e-commerce product categories. This was a personal project to practice data visualization and storytelling with real-world retail data.

---

## What this project is about

I came across this dataset on Kaggle and thought it would be interesting to dig into — not just because it covers India-specific buying patterns, but because the data has some genuinely surprising findings once you start slicing it by region and category.

The dashboard covers around 18,000 orders across three years, with data on cities, product categories, monthly trends, and profit breakdowns at the sub-category level.

---

## Dashboard Overview

**Live Dashboard:** https://public.tableau.com/views/IndiaSalesDashboard_17779880238590/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## Key Findings

**Indore leads all cities in sales volume** — which honestly surprised me. Mumbai comes in second, but Indore's dominance suggests strong Tier 2 city demand that often gets overlooked in national-level analysis.

**Tables and Chairs are losing money.** Despite being part of the Furniture category which looks healthy overall, these two sub-categories are consistently in the red. The category-level view masks this completely — which is exactly why sub-category analysis matters.

**January and November are peak months.** January likely captures post-holiday demand and New Year purchases. November's spike lines up with Diwali season shopping, which is expected but still clearly visible in the trend line.

**Electronics dominates revenue** at ₹19.83L, but Clothing and Furniture aren't far behind. The gap is smaller than you'd expect for an e-commerce platform.

**Profit margins are thin overall — 0.5%.** This is actually realistic for Indian e-commerce, where heavy discounting and logistics costs compress margins significantly. The dataset reflects real market conditions.

---

## Tools and Data

- **Visualization:** Tableau Desktop / Tableau Public
- **Data Source:** [Kaggle — India E-Commerce Dataset](https://www.kaggle.com/datasets/benroshan/ecommerce-data)
- **Data Size:** ~18,000 orders, 3 tables joined in Tableau
- **Time Period:** FY 2018–2019

---

## Dashboard Features

The dashboard has the following charts and interactive elements:

- KPI strip with Total Sales, Total Orders, Average Order Value, and Profit Margin
- State-wise sales choropleth map of India
- Monthly sales trend line (full year view)
- Category-wise horizontal bar chart
- Sub-category Profit & Loss chart with red/teal color coding
- Top 10 Cities by Sales
- Filters for State, Category, and Year parameter
