 ### Customer Behavior Analysis

Uncovering shopping trends, customer segments, and revenue drivers to help a retail company boost engagement, optimize marketing, and grow sales.


# Brief Summary

An end-to-end data analysis project on retail customer shopping behavior — involving SQL-based querying, Python-based EDA, and an interactive Power BI dashboard — to answer: "How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"

# Overview

This project analyzes a retail company's customer transaction dataset to surface actionable business insights. It covers revenue segmentation by gender and age, subscription behavior, discount effectiveness, product ratings, seasonal trends, and customer loyalty classification. The final output is a multi-page Power BI dashboard supported by SQL queries and a Python notebook.

# Problem Statement

A leading retail company wants to better understand its customers' shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty. The management team has noticed changes in purchasing patterns across demographics, product categories, and sales channels (online vs. offline). They are particularly interested in uncovering which factors — such as discounts, reviews, seasons, or payment preferences — drive consumer decisions and repeat purchases.
Core Business Question:

"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"


# Dataset

|   Detail       |                                                               Info                                                                  |
|----------------|-------------------------------------------------------------------------------------------------------------------------------------|
|   Records      |                                                        3,900 customers
|   Key Fields   | Customer ID, Gender, Age Group, Category, Item Purchased, Purchase Amount, Discount Applied, Subscription Status, Shipping Type, Payment  Method, Review Rating, Season, Previous Purchases |

# Tools & Technologies

|           Tool                  |              Purpose                  |
|---------------------------------|---------------------------------------|
|      SQL (PostgreSQL)           |   Data querying & business logic      |
|    Python (Jupyter Notebook)    |   Data cleaning, EDA & visualization  |
|         Power BI                |   Interactive dashboard & reporting   |

# Methods

1. Data Extraction (SQL) — Wrote 10 analytical queries covering revenue by gender, discount behavior, product ratings, shipping comparison, subscriber vs. non-subscriber spend, customer segmentation (New / Returning / Loyal), top products by category, repeat buyer behavior, and age-group revenue contribution.

2. Exploratory Data Analysis (Python) — Cleaned the dataset, handled missing values, created the Age_Group derived column, and produced visualizations for distributions, correlations, and trends using Pandas, Matplotlib, and Seaborn.

3. Dashboard (Power BI) — Built a 3-page interactive dashboard with KPI cards, bar charts, donut charts, and category filters to make insights accessible to business stakeholders.


💡 Key Insights

1  Male customers generate significantly higher total revenue than female customers (~$157K vs ~$76K).  
2  Young Adults lead revenue contribution across all age groups.  
3  Free Shipping and Standard Shipping are the most preferred shipping types.  
4  Subscribed customers generate nearly 2x the total revenue of non-subscribers, despite being fewer in count (~1K vs ~2.9K).  
5  43% of purchases were made with a discount applied.  
6  Fall is the highest-revenue season; Summer the lowest.  
7  PayPal, Credit Card, and Cash are the top 3 payment methods.  
8  Top-rated products (avg. rating 4): Gloves, Sandals, Boots, Hat, Skirt.  
9  Most purchased items: Blouse, Jewelry, Pants, Shirt, Dress.  
10  79.9% of customers are Loyal (>10 previous purchases); only 2.13% are New.  
11  Avg. rating is consistent across customer types (~3.7–3.8), suggesting satisfaction is stable regardless of loyalty.  


# Dashboard / Output
The Power BI dashboard is organized into 3 pages:
Page 1 — Revenue & Subscriber Overview
Show Image
KPI Cards: Total Customers (3,900) · Total Revenue ($233.08K) · Avg Purchase ($59.76) · Avg Rating (3.75)
Visuals: Revenue by Gender · Revenue by Age Group · Revenue by Shipping Type · Subscriber vs Non-Subscriber (Avg Spend, Total Revenue, Customer Count)

Page 2 — Buying Patterns & Trends
Show Image
Visuals: Discount Applied % (Donut) · Customers by Payment Method · Total Revenue by Season · Top 5 Products by Avg Rating · Top 3 Purchased Products by Category

Page 3 — Customer Loyalty Segmentation
Show Image
Visuals: Customer Type Distribution (Loyal / Returning / New) · Top 5 Products by Avg Rating (filterable by Category) · Avg Rating by Customer Type

# Results & Conclusion

The analysis reveals that subscription status, age group, and seasonal timing are the strongest drivers of revenue. The company should prioritize:

Expanding its subscriber base (they spend more and are more loyal)
Targeting Young Adult and Middle-aged demographics with personalized campaigns
Running promotions in Fall and Spring when spending peaks
Focusing inventory and marketing on high-rated, frequently purchased items like Blouses, Jewelry, and Sandals

# Author & Contact
KRISHNA
LinkedIn :- https://www.linkedin.com/in/krishna-krishna-26a106231/ 
