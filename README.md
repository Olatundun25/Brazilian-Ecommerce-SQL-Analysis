Brazilian E-Commerce Sales Analysis (SQL)
A complete SQL-based analysis of a Brazilian e-commerce platform (Olist), covering sales performance, customer behaviour, product trends, seller performance, and delivery efficiency across 99,442 orders.
---
Project Preview
> Upload your query screenshots to a folder called `screenshots` in this repo and they will show here.
---
Key Metrics
Metric	Value
Total Revenue	$13,591,643.70
Total Orders	98,666
Average Order Value	$120.65
Total Products	32,952
Total Sellers	3,096
Average Delivery Time	3.2 days
Cancellation Rate	0.63%
Delivery Success Rate	97%
---
Key Insights
Revenue grew massively over time from $134.97 in the first month to $838,576.64 in the last month, showing strong and consistent business growth
SP (Sao Paulo) dominates all states with $5,202,955 in revenue and 41,375 orders, accounting for nearly 40% of total revenue
97% of orders were successfully delivered with an average delivery time of just 3.2 days, showing excellent logistics performance
Cancellation rate is very low at 0.63% indicating high customer satisfaction and order fulfilment reliability
Top seller generated $229,472 in revenue from 1,132 orders while the top product generated $63,885 from 195 orders
Most customers placed only 1 order suggesting low repeat purchase rate, which is an opportunity for the business to improve customer retention
Average order contains only 1.14 items suggesting customers mostly buy single items per order
---
Business Recommendations
Based on the analysis, here are actionable steps the business can take:
Focus marketing efforts on SP, RJ, and MG states as they generate the most revenue
Investigate why most customers only order once and introduce loyalty programs to improve retention
Replicate the success of top sellers by studying their pricing and product strategy
Expand into lower performing states with targeted promotions
Maintain the excellent 3.2 day delivery time as it is a key competitive advantage
---
Dataset Details
Source: Brazilian E-Commerce Public Dataset by Olist via Kaggle
Link: kaggle.com/datasets/olistbr/brazilian-ecommerce
Tables used: 5
Table	Rows	Description
orders	99,442	Order details and status
customers	99,442	Customer location and ID
order_items	112,651	Products in each order
products	32,952	Product details
sellers	3,096	Seller information
---
SQL Concepts Used
SELECT, WHERE, GROUP BY, ORDER BY
AGGREGATE FUNCTIONS: SUM, COUNT, AVG, ROUND
JOINS: INNER JOIN across multiple tables
SUBQUERIES
CASE WHEN statements
UNION ALL
Date functions: strftime, julianday
HAVING clause
LIMIT
---
Project Structure
```
Brazilian-Ecommerce-SQL-Analysis/
|-- ecommerce_analysis.sql         # All SQL queries used in the analysis
|-- screenshots/                   # Folder containing query result screenshots
|   |-- total_rows.png
|   |-- order_status_breakdown.png
|   |-- top_products.png
|   |-- top_sellers.png
|   |-- top_customers.png
|   |-- revenue_by_state.png
|   |-- monthly_trend.png
|-- README.md                      # Project documentation
```
---
How to Run
Download the dataset from kaggle.com/datasets/olistbr/brazilian-ecommerce
Go to sqliteonline.com and connect to SQLite
Import these 5 CSV files: orders, customers, order_items, products, sellers
Make sure to tick the header row option when importing
Open `ecommerce_analysis.sql` and run each query section by section
---
Tools Used
SQL (SQLite) - All data analysis and querying
SQLiteOnline - Browser based SQL workspace
Excel - Initial data exploration
---
Author
Adeyemo Taiwo Aminat
Data Analyst | Excel | Power BI | Tableau | SQL
LinkedIn: Adeyemo Oluwakemisola
GitHub: Olatundun25
Email: Adeyemotaiwo2019@gmail.com
---
License
This project is open source and available for learning and portfolio purposes.
