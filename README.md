# E-Commerce Sales & Profit Analysis

## Project Overview

This project analyzes e-commerce sales transactions to evaluate **sales performance, profitability, product performance, customer segments, regional trends, and the impact of discounts on profit**. The project follows an end-to-end Data Analytics workflow, including data cleaning, exploratory data analysis, SQL analysis, data modeling, and interactive Power BI dashboard development.

## Business Objectives

- Analyze overall sales, profit, orders, and customer performance.
- Identify top-performing and loss-making products.
- Compare sales and profitability across categories and sub-categories.
- Analyze regional and customer-segment performance.
- Identify sales and profit trends over time.
- Examine the relationship between discounts and profitability.
- Generate actionable business insights and recommendations.

## Tools & Technologies

- **Excel** – Initial data inspection and basic data cleaning
- **Python** – Data cleaning, feature engineering and exploratory data analysis
- **Pandas & NumPy** – Data manipulation and analysis
- **Matplotlib** – Data visualization
- **MySQL** – SQL-based business analysis
- **Power BI** – Data modeling, DAX measures and interactive dashboard
- **GitHub** – Project documentation and portfolio management

## Data Modeling

A **Star Schema** was implemented in Power BI to improve data organization and analytical performance.

### Fact Table
- FactSales

### Dimension Tables
- DimDate
- DimCustomer
- DimProduct
- DimLocation

Relationships were created using primary and foreign keys with **one-to-many relationships** between dimension and fact tables.

## Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate records
- Incorrect data types
- Invalid date values
- Formatting inconsistencies
- Numerical data quality issues

Legitimate negative-profit transactions were retained because they provide valuable information for profitability analysis.

## Python Analysis

Python and Pandas were used to:

- Inspect dataset structure and data types
- Analyze missing and duplicate records
- Convert and extract date components
- Create derived metrics such as profit margin and shipping days
- Analyze sales and profit by category, sub-category, region and customer segment
- Analyze monthly sales trends
- Examine the relationship between discount and profit

## SQL Analysis

MySQL was used to perform business-focused analysis using:

- Aggregations
- GROUP BY
- CASE WHEN
- Subqueries
- CTEs
- Window functions
- Ranking
- Top and bottom product analysis

## Power BI Dashboard

A two-page interactive dashboard was developed.

### Page 1 — Executive Overview

Includes:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Margin
- Sales & Profit Trend
- Sales by Category
- Profit by Category
- Sales by Region
- Sales by Customer Segment

### Page 2 — Product & Profitability Analysis

Includes:

- Top 10 Products by Sales
- Bottom 10 Products by Sales
- Top 10 Products by Profit
- Bottom 10 Products by Profit
- Discount vs Profit Analysis
- Sub-category sales matrix


Interactive slicers allow users to analyze results by **Year, Region, Category, Segment and Sub-Category**.

## Key Insights

The analysis focuses on identifying:

- High-revenue and high-profit categories
- Products contributing to overall losses
- Regional differences in sales and profitability
- Customer segments driving revenue
- Sub-categories with weak profit margins
- Potential relationships between discount levels and profitability

## Business Recommendations

Based on the analysis, recommendations can include:

- Reviewing discount strategies for low-margin products.
- Investigating products with consistently negative profitability.
- Focusing resources on high-profit categories and products.
- Reviewing regional performance to identify opportunities for improvement.
- Using product-level profitability analysis to support pricing and promotional decisions.

## Project Workflow

**Excel → Python/Pandas → MySQL → Power BI Data Modeling → DAX → Dashboard → Business Insights**

## Project Outcome

The project demonstrates an end-to-end ability to transform raw e-commerce transaction data into **cleaned data, analytical insights, business-focused SQL analysis, a structured star-schema data model, and an interactive Power BI dashboard**.
