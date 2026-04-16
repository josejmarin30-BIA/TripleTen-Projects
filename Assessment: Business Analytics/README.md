📊 E-Commerce User Behavior Analysis: Conversion Funnel & Cohort Retention

Author: Jose Marin
Role: Data / Business Analyst
Tools: Excel | Google Sheets | Pivot Tables | Data Cleaning | Data Analysis
Skills: Conversion Funnel Analysis, Cohort Analysis, Retention Metrics, Business Analytics, Customer Behavior Analysis

📌 Project Overview

This project analyzes raw user activity logs from an e-commerce platform to evaluate customer behavior and measure key business performance metrics. The objective was to transform event-level data into meaningful insights by building a conversion funnel and performing cohort-based retention analysis.

Using spreadsheet tools, I cleaned and prepared transactional data, calculated customer conversion rates, and tracked user retention over time. The analysis provided stakeholders with insights into how effectively the website converts visitors into customers and how customer engagement changes after the first purchase.

🎯 Business Problem

The executive team needed visibility into customer behavior to improve website performance and increase revenue. Specifically, they wanted to understand:

How effectively users convert from browsing to purchasing
Where customers drop off in the purchase process
How long customers remain engaged after their first purchase
Whether retention rates improve or decline over time

This project focused on turning raw event logs into actionable business metrics to support customer growth and retention strategies.

🗂️ Dataset Description

The dataset contains user interaction logs from an e-commerce website. Each row represents a single user event.

Raw User Activity Dataset
Column	Description
user_id	Unique customer identifier
event_type	User activity (view, cart, purchase)
category_code	Product category
brand	Product manufacturer
price	Product price (USD)
event_date	Date of activity
🔎 Analysis Tasks
Part 1: Conversion Funnel Analysis

A three-stage conversion funnel was created using pivot tables to measure how users move through the purchasing process.

Funnel Stages
Product View
Cart Open
Purchase
Metrics Calculated
Unique users at each stage
Total conversion rate
Step-to-step conversion rate

This analysis identified potential drop-off points in the customer journey.

Part 2: Data Preparation for Cohort Analysis

Purchase data was isolated and transformed to support retention tracking.

Steps Performed
Filtered purchase events from raw activity logs
Created a dedicated purchase dataset
Calculated the first purchase date for each user
Grouped transactions by month
Calculated time differences between purchases
New Columns Created
first_purchase_date
event_month
first_purchase_month
cohort_age

These transformations enabled accurate cohort tracking.

Part 3: Cohort Retention Analysis

Customers were grouped into cohorts based on the month of their first purchase, and retention rates were calculated over time.

Retention Formula

Retention Rate = Returning Users ÷ Original Cohort Size

This analysis measured customer loyalty and repeat purchasing behavior.

Part 4: Reporting & Documentation

The spreadsheet was structured and formatted for executive-level reporting.

Deliverables Included
Conversion funnel analysis
Cohort retention analysis
Executive summary
Table of contents
Documented assumptions
Formatted tables and visuals
📈 Key Insights
A significant portion of users dropped off between viewing products and completing purchases
Conversion rates revealed opportunities to improve the checkout process
Customer retention declined gradually after the first purchase
Early cohort engagement strongly influenced long-term retention
Repeat purchasing behavior varied across customer groups
💡 Business Recommendations

Based on the analysis, the following recommendations were provided:

Improve the checkout experience to reduce customer drop-off
Implement targeted marketing campaigns for new customers
Monitor retention rates to evaluate customer loyalty
Focus on improving early customer engagement
Use cohort data to guide customer retention strategies
🛠️ Skills Demonstrated
Technical Skills (Hard Skills)
Data Cleaning and Preparation
Pivot Tables
Conversion Funnel Analysis
Cohort Analysis
Retention Rate Calculation
Spreadsheet Modeling
Data Aggregation
Data Transformation
Business Analytics
KPI Development
Analytical & Professional Skills (Soft Skills)
Analytical Thinking
Problem Solving
Attention to Detail
Data Interpretation
Business Decision Support
Communication of Insights
Stakeholder Reporting
Critical Thinking
📂 Repository Structure
ecommerce-conversion-cohort-analysis/
│
├── data/
│   └── raw_user_activity.xlsx
│
├── analysis/
│   ├── conversion_funnel.xlsx
│   ├── cohort_analysis.xlsx
│   └── retention_rates.xlsx
│
├── documentation/
│   ├── executive_summary.xlsx
│   └── table_of_contents.xlsx
│
└── README.md
🚀 Project Outcome

This project demonstrates the ability to transform raw user activity logs into meaningful business metrics using spreadsheet-based analytics. By analyzing conversion behavior and customer retention patterns, the project provided actionable insights to support data-driven decision-making in an e-commerce environment.
