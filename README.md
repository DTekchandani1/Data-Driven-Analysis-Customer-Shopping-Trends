Data Driven Analysis Customer Shopping Trends

1.	Problem Statement
A leading retail company wants to better understand its customers’ shopping behavior to improve sales, customer satisfaction, and long-term loyalty. The objective is to analyze purchasing patterns across demographics, product categories, and sales channels to identify key drivers such as discounts, reviews, seasons, and payment preferences that influence repeat purchases and engagement.

2.	Dataset Summary

•	Rows: 3,900
•	Columns: 18
•	Customer Demographics: Age, Gender, Location, Subscription Status
•	Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
•	Shopping Behavior: Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type
•	Missing Data: 37 values in Review Rating column
3.	Data Preparation & Cleaning (Python)

•	Data Loading using pandas
•	Initial Exploration using df.info() and df.describe()
 
•	Handled missing values by imputing median rating per category
•	Standardized column names to snake_case
•	Feature Engineering: Created age_group and purchase_frequency_days
•	Data consistency check for discount_applied and promo_code_used
•	Integrated cleaned data into SQL Server Management for SQL analysis

4.	Data Analysis Using SQL

•	Revenue analysis by gender






 

 
•	Top 3 products per category
 
•	High-spending discount users
 
•	Customer segmentation insights
 
•	Sales trends by age group and shipping type
 
5.	Tools & Technologies
•	Microsoft Power BI
•	Power Query (Data Cleaning & Transformation
•	DAX (Data Analysis Expressions)
•	Data Modeling
6.	Key Dashboard Metrics
•	Total Customers: 3,900
•	Average Review Rating: 3.76
•	Average Purchase Amount: $59.57
•	Revenue by Category
•	Sales by Age Group
•	Subscription-Based Customer %
7.	Key Insights
•	Customers with subscriptions show higher engagement.
•	Clothing and Accessories contribute significantly to revenue.
•	Middle-aged customers form the largest purchasing segment.
•	Average rating indicates moderate customer satisfaction.
8.	 DAX Measures Used
Examples:
•	Total Customers = COUNT(Customer[Customer ID])
•	Average Purchase = AVERAGE(Customer[Purchase Amount])
•	Average Rating = AVERAGE(Customer[Review Rating])
9.	Dashboard Features
•	Interactive slicers (Gender, Category, Subscription Status)
•	KPI Cards
•	Donut & Bar Charts
•	Category-wise revenue analysis
•	Age-based sales comparison
 
10. Business Recommendations

•	Boost Subscriptions: Promote exclusive benefits for subscribers
•	Customer Loyalty Programs: Reward repeat buyers to move them into the loyal segment
•	Review Discount Policy: Balance sales boosts with margin control
•	Product Positioning: Highlight top-rated and best-selling products in campaigns
•	Targeted Marketing: Focus on high-revenue age groups and express-shipping users















