# Customer_Behavior_Data_Analytics

Overview

This project analyzes customer shopping behavior to identify purchasing trends, customer demographics, and factors influencing buying decisions.
The goal is to simulate a real-world data analytics workflow, starting from raw data cleaning to business insights and dashboard visualization.

The project follows an end-to-end analytics pipeline using Python, SQL, and Power BI to transform raw data into actionable insights for business decision-making.

Business Problem

A retail company wants to better understand customer purchasing patterns in order to:

Improve marketing strategies

Increase customer engagement

Optimize product and pricing strategies

Identify key revenue-driving customer segments

This analysis explores how factors like discounts, customer demographics, subscription status, and shipping preferences influence purchasing behavior.

Tools & Technologies

Python (Pandas, Jupyter Notebook) – Data cleaning and preprocessing

PostgreSQL – Data storage and business analysis using SQL

Power BI – Interactive dashboard creation

GitHub – Project documentation and version control

Dataset

The dataset contains information about customer purchases including:

Customer demographics (Age, Gender)

Purchase details (Item Purchased, Category, Purchase Amount)

Product attributes (Color, Size, Season)

Customer behavior metrics (Previous Purchases, Frequency of Purchases)

Promotional activity (Discount Applied, Promo Code Used)

Customer feedback (Review Rating)

Each row represents one customer's latest purchase behavior.

Project Workflow
1. Data Cleaning & Preparation (Python)

Loaded dataset using Pandas

Handled missing values in review ratings using category-level median imputation

Standardized column names using snake_case

Created new features:

Age Group segmentation

Purchase frequency in days

Removed redundant columns to improve dataset consistency

2. Data Analysis (SQL)

The cleaned dataset was stored in PostgreSQL for deeper analysis.

Key analyses performed:

Revenue comparison between male and female customers

Customers using discounts but spending above average

Top-rated products based on review ratings

Impact of subscription status on spending behavior

Customer segmentation into new, returning, and loyal customers

Identifying top-selling products within each category

Revenue analysis across age groups

Advanced SQL techniques used:

Aggregations

Subqueries

Common Table Expressions (CTEs)

Window functions

3. Dashboard Creation (Power BI)

An interactive Power BI dashboard was created to visualize insights.

Key dashboard components:

KPI Cards

Total Customers

Average Purchase Amount

Average Review Rating

Visualizations

Revenue by Category

Sales by Category

Revenue by Age Group

Sales by Age Group

Customer Subscription Distribution

Interactive filters allow users to explore data by:

Gender

Category

Subscription Status

Shipping Type

Key Insights

Some important findings from the analysis include:

Young adults generated the highest revenue

Customers choosing express shipping spent more on average

Several products showed high dependency on discounts

Loyal customers formed the largest customer segment

These insights can help businesses design targeted marketing campaigns and pricing strategies.

Repository Structure
Customer-Behavior-Analysis
│
├── dataset
│   └── customer_shopping_behavior.csv
│
├── python
│   └── data_cleaning_analysis.ipynb
│
├── sql
│   └── business_analysis_queries.sql
│
├── powerbi
│   └── customer_behavior_dashboard.pbix
│
├── report
│   └── project_report.pdf
│
└── README.md
Future Improvements

Potential enhancements for the project:

Add machine learning models for purchase prediction

Perform customer lifetime value analysis

Integrate real-time data pipelines

Expand dataset to include full transaction history

Author

Vinayak Purohit
B.Tech Computer Science | Aspiring Data Analyst

Skills: Python, SQL, Power BI, Tableau, Advanced Excel, Data Analysis

Connect

If you found this project interesting or have suggestions, feel free to connect with me on LinkedIn.
