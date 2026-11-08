 E-Commerce Sales Performance Analysis & Dashboard

 📊 Project Overview

This project analyzes e-commerce sales data to understand overall sales performance, customer activity, product category performance, regional performance, payment methods, and sales trends over time.

The project follows a practical data analytics workflow, starting with raw sales data, followed by data cleaning and validation using Python and Pandas, exploratory analysis, and finally the development of an interactive Power BI dashboard.

The goal was to transform raw transactional data into clear business insights that can support better decision-making.


## 🎯 Business Objective

The main objective of this project was to answer key business questions such as:

- How much revenue was generated?
- How many orders were placed?
- What is the average order value?
- How many unique customers are represented in the data?
- Which product category generates the most revenue?
- Which region performs best?
- Which payment method is most commonly used?
- How does revenue change over time?
- What relationships exist between pricing, quantity, discounts, delivery time, and other performance indicators?
- What insights and business actions can be derived from the analysis?

---

## 📁 Dataset

The dataset contains **5,000 e-commerce sales transactions** with information about orders, customers, products, pricing, discounts, payments, delivery, ratings, and revenue.

### Original Columns

| Column | Description |
|---|---|
| `order_id` | Unique identifier for each order |
| `order_date` | Date the order was placed |
| `customer_id` | Customer identifier |
| `product_category` | Product category |
| `region` | Customer/order region |
| `quantity` | Number of units purchased |
| `unit_price` | Price per unit |
| `discount` | Discount applied to the order |
| `payment_method` | Payment method used |
| `delivery_days` | Number of days required for delivery |
| `customer_rating` | Customer rating |
| `revenue` | Revenue generated from the order |

The dataset was used as a practical portfolio dataset to simulate a real-world e-commerce analytics scenario.

---

## 🛠️ Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**
- **Power BI**
- **GitHub**

---

## 🔄 Data Analysis Workflow

The project followed these main stages:

### 1. Data Inspection

The raw dataset was inspected to understand:

- Number of rows and columns
- Data types
- Missing values
- Duplicate records
- Unique values
- Numerical ranges
- Categorical values
- Potential data quality issues

The dataset contained **5,000 rows and 12 original columns**.

---

### 2. Data Cleaning

Python and Pandas were used to prepare the data for analysis.

The cleaning process included:

- Checking for missing values
- Checking for duplicate records
- Checking for duplicate `order_id` values
- Standardizing categorical values
- Converting `order_date` into a proper datetime format
- Validating numerical fields
- Checking discount values
- Checking customer ratings
- Checking delivery days
- Validating revenue calculations

---

### 3. Data Validation

Revenue was independently recalculated using:

Quantity × Unit Price × (1 − Discount)
The calculated revenue was compared with the original revenue column.
The difference was within approximately ±0.005, indicating that the small differences were caused by rounding rather than a significant calculation issue.
Temporary validation columns were removed after the check.
4. Feature Engineering
Additional columns were created to support the analysis:
•	year
•	month
•	month_name
•	discount_amount
•	gross_sales
These additional fields made it easier to analyze sales trends, discounts, and gross versus net sales.
📈 Exploratory Data Analysis
Several areas of the dataset were analyzed.
Overall Sales Performance
Key metrics from the dataset:
Metric	Result
Total Revenue	5,109,775.74
Total Orders	5,000
Average Order Value	1,021.96
Unique Customers	989
Total Quantity Sold	20,224
Gross Sales	6,240,021.96
Discount Amount	1,130,246.08
Product Category Performance
Product categories were compared based on:
•	Revenue
•	Number of orders
•	Units sold
•	Average order value
Electronics generated the highest revenue among the product categories and also recorded the highest order volume and unit sales in this dataset.
Electronics generated approximately 36% of total revenue.
Regional Performance
The four regions were compared based on revenue, orders, units sold, and average order value.
The West recorded the highest:
•	Revenue
•	Number of orders
•	Units sold
The West generated approximately 26% of total revenue.
Payment Method Analysis
The dataset contains three payment methods:
•	Card
•	Cash on Delivery (COD)
•	Wallet
Card recorded the highest number of orders and the highest revenue among the payment methods.
Card transactions represented approximately 46% of total revenue.
Customer Analysis
The dataset contains 989 unique customers.
Customer purchasing behavior was examined by grouping orders and revenue by customer.
The analysis found that:
•	950 customers placed more than one order.
•	39 customers placed only one order.
•	Approximately 96.1% of customers were repeat customers within this dataset.
This indicates a high level of repeat purchasing activity in the dataset.
Relationship Analysis
Correlation analysis was used to explore relationships between numerical variables.
The strongest observed relationships with revenue were:
Variable	Correlation with Revenue
Unit Price	0.678
Quantity	0.624
Discount	-0.139
Unit price and quantity showed the strongest positive linear relationships with revenue.
Discount showed a weak negative linear relationship with revenue.
These correlations describe relationships in the dataset and should not be interpreted as proof of causation.
Delivery Time & Customer Rating
The relationship between delivery time and customer rating was also examined.
The Pearson correlation was approximately:
-0.018
This indicates almost no linear relationship between delivery time and customer rating in this dataset.
Therefore, other factors may be more relevant when investigating customer satisfaction.
📊 Power BI Dashboard
An interactive Power BI dashboard was created to provide a visual overview of the sales performance.
Dashboard Components
The dashboard includes:
•	Total Revenue
•	Total Orders
•	Average Order Value
•	Unique Customers
•	Monthly Revenue Trend
•	Revenue by Product Category
•	Revenue by Region
•	Revenue by Payment Method
•	Key Business Insights
Dashboard Preview
Add a screenshot of the final dashboard to the images folder and name it:
dashboard.png
Then this image can be displayed here:
💡 Key Insights
1. Overall Sales Performance
The dataset generated approximately 5.11 million in revenue across 5,000 orders, with an average order value of approximately 1,021.96.
This provides a high-level view of the overall sales performance represented in the dataset.
2. Electronics Was the Leading Category
Electronics generated the highest category revenue and also recorded the highest order volume and unit sales.
This makes Electronics an important category for further product-level analysis.
3. The West Was the Leading Region
The West recorded the highest revenue, order volume, and unit sales among the four regions.
Further analysis could investigate the products, customers, and purchasing patterns contributing to this performance.
4. Card Was the Dominant Payment Method
Card recorded the highest number of transactions and generated the highest revenue among the payment methods.
This suggests that card transactions represent an important part of the sales activity in the dataset.
5. High Repeat Customer Activity
Approximately 96.1% of customers placed more than one order in the dataset.
This provides an opportunity to further investigate customer purchasing frequency, customer lifetime value, and retention patterns.
6. Pricing and Quantity Were Strongly Associated with Revenue
Unit price and quantity had the strongest positive correlations with revenue.
Because revenue is mathematically calculated using both quantity and price, these relationships are expected and should not automatically be interpreted as causal business effects.
7. Delivery Time Had Almost No Linear Relationship with Ratings
The correlation between delivery time and customer rating was approximately -0.018, indicating almost no linear relationship in this dataset.
Other factors should therefore be investigated when analyzing customer satisfaction.
📌 Business Recommendations
Based on the analysis, the following areas could be investigated further:
Product Performance
Analyze individual products within the Electronics category to identify high-performing and underperforming products.
Regional Strategy
Investigate the factors contributing to stronger performance in the West, including product mix, customer behavior, and order volume.
Customer Retention
Since the dataset contains a high proportion of repeat customers, further analysis could examine purchasing frequency, customer lifetime value, and customer segments.
Pricing & Discount Strategy
Analyze how different price points and discount levels are associated with order value and revenue before making pricing decisions.
Payment Experience
Monitor payment-method performance and investigate whether different payment methods are associated with differences in order value, customer behavior, or transaction volume.
Customer Satisfaction
Since delivery time showed almost no linear relationship with ratings, investigate other variables such as product category, order value, payment method, or customer history.
📂 Project Structure
E-Commerce-Sales-Performance-Analysis/
│
├── data/
│   ├── ecommerce_sales_analytics_5000.csv
│   └── ecommerce_sales_cleaned.csv
│
├── notebooks/
│   └── ecommerce_sales_analysis.ipynb
│
├── dashboard/
│   └── Ecommerce_Sales_Performance_Analysis.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
🚀 Skills Demonstrated
This project demonstrates practical experience in:
•	Data cleaning
•	Data validation
•	Exploratory data analysis
•	Feature engineering
•	Data aggregation
•	Group-by analysis
•	Correlation analysis
•	Business insight generation
•	Data visualization
•	Dashboard development
•	Power BI reporting
•	Communicating analytical findings
•	Translating data into business recommendations
📌 Project Outcome
The project transformed raw e-commerce transaction data into a cleaned analytical dataset and an interactive Power BI dashboard.
The analysis provides a structured view of:
Sales → Customers → Products → Regions → Payments → Trends → Insights
The project demonstrates an end-to-end approach to turning raw data into information that can support business analysis and decision-making.
👤 Author
Bashir Lawan Isyaku
Data Analyst | Python | SQL | Excel | Power BI
