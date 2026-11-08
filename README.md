# Retail Sales Performance Analysis

An end-to-end data analytics project analysing 5,000 retail transactions using Python and Microsoft Power BI to evaluate sales performance, customer purchasing behaviour, product category performance, and regional revenue.

## Project Overview

This project focuses on analysing retail sales data to uncover meaningful insights into business performance.

The analysis involved cleaning and preparing transaction data using Python, performing exploratory data analysis (EDA), calculating key performance indicators (KPIs), and developing an interactive Power BI dashboard.

The goal was to understand revenue performance, identify top-performing product categories and regions, examine payment preferences, and provide insights that could support better business decisions.

## Project Objectives

- Evaluate overall sales and revenue performance.
- Analyse monthly sales trends.
- Identify top-performing product categories.
- Compare revenue performance across regions.
- Examine customer purchasing behaviour.
- Analyse payment method preferences.
- Investigate factors associated with revenue.
- Build an interactive Power BI dashboard.
- Communicate findings through actionable business insights.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and analysis |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Jupyter Notebook | Exploratory data analysis |
| Microsoft Power BI | Dashboard development |
| DAX | KPI calculations and measures |

## Dataset Description

The project used a retail/e-commerce transaction dataset containing **5,000 orders**.

Important dataset columns included:

| Column | Description |
|---|---|
| order_id | Unique order identifier |
| order_date | Date of transaction |
| customer_id | Customer identifier |
| product_category | Category of purchased product |
| region | Sales region |
| quantity | Number of units purchased |
| unit_price | Price per unit |
| discount | Discount applied |
| payment_method | Payment method used |
| delivery_days | Number of days taken for delivery |
| customer_rating | Customer rating |
| revenue | Revenue generated from the transaction |

## Data Cleaning and Preparation

Python and Pandas were used to prepare the dataset for analysis.

The preparation process included:

1. Loading and inspecting the dataset.
2. Examining dataset dimensions, column names, and data types.
3. Checking for missing values and duplicate records.
4. Handling data quality issues.
5. Converting date and numerical columns into appropriate data types.
6. Validating numerical values and sales calculations.
7. Preparing the cleaned dataset for exploratory analysis.
8. Exporting the processed data for Power BI.

## Exploratory Data Analysis

The analysis focused on understanding sales performance and customer behaviour.

### 1. Sales Performance Analysis

Examined total revenue, order volume, and average order value to understand the overall performance of the business.

### 2. Product Category Analysis

Compared revenue and sales volume across product categories to identify the strongest contributors to business performance.

### 3. Regional Analysis

Investigated revenue performance across different sales regions to identify high-performing and lower-performing markets.

### 4. Payment Method Analysis

Examined customer payment preferences and compared transaction volumes across payment methods.

### 5. Customer Analysis

Investigated customer purchasing behaviour, including repeat purchasing patterns.

### 6. Correlation Analysis

Examined relationships between numerical variables and revenue.

Notable correlation results included:

| Variable | Correlation with Revenue |
|---|---:|
| Unit Price | +0.678 |
| Quantity | +0.624 |
| Discount | -0.139 |
| Delivery Days | -0.0177 |
| Customer Rating | -0.0177 |

These values indicate that unit price and quantity had the strongest positive linear relationships with revenue among the variables examined. Correlation does not establish causation.

## Key Performance Indicators (KPIs)

The analysis produced the following results:

| KPI | Result |
|---|---:|
| Total Revenue | 5,109,775.74 |
| Total Orders | 5,000 |
| Total Customers | 989 |
| Average Order Value | 1,021.96 |
| Repeat Customers | 950 |

## Key Findings

1. **Overall revenue:** The business generated total revenue of 5,109,775.74 across 5,000 orders.

2. **Average order value:** The average revenue per order was approximately 1,021.96.

3. **Top-performing category:** Electronics generated the highest revenue, contributing 1,829,899.22, with 7,109 units sold.

4. **Regional performance:** The West region recorded the highest revenue at 1,345,582.16.

5. **Payment preferences:** Card payments recorded the highest transaction volume, with 2,270 orders.

6. **Customer retention pattern:** 950 out of 989 customers made repeat purchases, indicating a high level of repeat purchasing in the dataset.

7. **Revenue relationships:** Unit price and quantity had the strongest positive correlations with revenue among the numerical variables examined.

## Power BI Dashboard

An interactive dashboard was developed in Microsoft Power BI to present the major findings.

The dashboard included:

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Monthly Revenue Trends
- Revenue by Product Category
- Revenue by Region
- Orders by Payment Method

The dashboard was designed to provide a clear overview of sales performance and allow users to explore different aspects of the business.

**Dashboard screenshots:**

Add your dashboard screenshots to a `screenshots` folder and reference them below.

![Retail Sales Dashboard](screenshots/retail_sales_dashboard.png)

## Business Insights and Recommendations

Based on the analysis, the following recommendations were identified:

### 1. Strengthen Electronics Sales

Electronics was the highest revenue-generating category. The business could investigate opportunities to maintain its performance through product availability, promotions, and effective inventory planning.

### 2. Investigate Regional Performance

The West region recorded the highest revenue. The business should examine the factors contributing to its performance and identify opportunities to apply successful strategies in other regions.

### 3. Maintain Customer Relationships

The high number of repeat customers suggests an opportunity to strengthen customer loyalty through personalized offers, customer engagement, and improved shopping experiences.

### 4. Monitor Payment Preferences

Card payments accounted for the largest number of orders. The business should continue supporting convenient payment methods while monitoring changes in customer preferences.

### 5. Monitor Revenue Drivers

Unit price and quantity showed strong positive correlations with revenue. The business should monitor product pricing, sales volume, and product mix when evaluating revenue performance.

## Conclusion

This project demonstrated the use of Python and Microsoft Power BI to transform retail transaction data into meaningful business insights.

Through data cleaning, exploratory data analysis, KPI calculations, and interactive visualization, the project provided an overview of revenue performance, product category contributions, regional sales, payment preferences, and customer purchasing behaviour.

The findings highlighted Electronics as the leading revenue-generating category, the West as the highest-performing region, and repeat purchasing as an important feature of the customer base.

Overall, the project strengthened practical skills in Python, Pandas, data cleaning, exploratory data analysis, descriptive statistics, correlation analysis, Power BI, DAX, and business insight communication.

---

**Project Category:** Data Analytics

**Dataset Size:** 5,000 orders

**Tools:** Python, Pandas, NumPy, Jupyter Notebook, Microsoft Power BI, DAX

**Deliverable:** Interactive Power BI Sales Performance Dashboard
