🏙️ Manhattan Vacation Rental Market Analysis

Author: Jose Marin
Role: Data / Business Analyst
Tools: Excel | Google Sheets | Pivot Tables | Data Cleaning | Data Visualization
Skills: Data Analysis, Revenue Forecasting, Business Intelligence, Decision Support

📌 Project Overview

This project analyzes the Manhattan vacation rental market to identify the most profitable property investment opportunities. The goal was to determine which neighborhoods and property sizes generate the highest demand and revenue, and to provide data-driven recommendations for investors interested in short-term rental properties.

Using Airbnb listing and calendar datasets, I performed data cleaning, exploratory data analysis, and revenue estimation to evaluate rental demand and financial performance. Reviews from the last 12 months were used as a proxy for rental frequency, while nightly pricing data was used to estimate annual revenue potential.

🎯 Business Problem

Real estate investors needed guidance on where to invest in Manhattan vacation rentals. Specifically, they wanted to understand:

Which neighborhoods have the highest rental demand
What property sizes are most popular among guests
How much revenue top-performing listings generate
Which property types provide the best return on investment

This analysis focused on identifying high-demand locations and estimating potential annual earnings to support strategic investment decisions.

📂 Dataset Description
Listings Dataset
Column	Description
listing_id	Unique property identifier
neighborhood	Property location
bedrooms	Number of bedrooms
number_of_reviews_ltm	Reviews in last 12 months
Calendar Dataset
Column	Description
listing_id	Property identifier
date	Booking date
available	Rental availability
adjusted_price	Nightly rental price
🧹 Data Cleaning Process

The dataset contained inconsistencies and missing values that required cleaning before analysis.

Steps performed:

Created a copy of the raw dataset
Standardized neighborhood names
Removed trailing spaces
Fixed inconsistent capitalization
Replaced missing bedroom values with 0 (studio apartments)
Created new cleaned columns
Documented changes in a change log

New Columns Created

neighborhood_clean
bedrooms_clean
revenue_earned
top_listing

These steps ensured data accuracy, consistency, and reproducibility.

📊 Methodology
Step 1: Identify High-Demand Neighborhoods

A pivot table was used to analyze demand based on the number of reviews in the last 12 months.

Metric Used:
Reviews were used as a proxy for rental frequency.

Top 3 Neighborhoods

Harlem
Hell's Kitchen
Lower East Side

A bar chart visualization was created to compare demand across the top 10 neighborhoods.

Step 2: Determine Most Popular Property Sizes

A second pivot table was used to analyze bedroom distribution.

Most Popular Property Sizes

1-bedroom — Most popular
Studios — Second most popular
2-bedrooms — Third most popular

Most neighborhoods showed strong demand for 1-bedroom properties.

Step 3: Revenue Estimation

Revenue was calculated using daily pricing data from the calendar dataset.

Formula Used

=IF(available="f", adjusted_price, 0)

This calculated revenue only when the property was rented.

Revenue Aggregation Formula

=SUMIF(calendar!$A$2:$A$72554, A2, calendar!$H$2:$H$72554)

Annual Revenue Estimate

Annual Revenue = 30-Day Revenue × 12

Listings were then ranked based on total revenue.

📈 Key Insights
High-demand neighborhoods consistently showed strong rental activity
1-bedroom units generated the highest demand across most locations
Studio apartments were most popular in Midtown
Revenue varied significantly across listings
Demand patterns supported targeted investment strategies
💡 Business Recommendations

Based on the analysis, the following investment strategy is recommended:

Invest in 1-bedroom properties in high-demand neighborhoods
Consider studio apartments in Midtown
Prioritize listings with strong review activity
Focus on properties with consistent revenue performance

These recommendations help investors maximize profitability and reduce investment risk.

📌 Project Deliverables
Cleaned dataset
Pivot table analysis
Revenue calculations
Data visualizations
Executive summary
Investment recommendations
🛠️ Skills Demonstrated
Technical Skills
Data Cleaning
Pivot Tables
Data Analysis
Excel / Google Sheets
Data Visualization
Revenue Forecasting
Spreadsheet Modeling
Business Intelligence
Analytical Skills
Market Analysis
Trend Identification
KPI Analysis
Decision Support
Problem Solving
Stakeholder Communication
🚀 How to Use This Project
Download the dataset
Open the spreadsheet
Review the cleaned data sheet
Explore pivot tables
View charts and analysis
Read the executive summary
📎 Repository Structure
Manhattan-Vacation-Rental-Analysis/
│
├── data/
│   ├── raw_data.xlsx
│   └── cleaned_data.xlsx
│
├── analysis/
│   ├── pivot_tables.xlsx
│   └── charts.xlsx
│
├── documentation/
│   ├── change_log.xlsx
│   └── executive_summary.docx
│
└── README.md
