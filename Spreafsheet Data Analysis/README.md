Manhattan Vacation Rental Market Analysis
Tools: Excel / Google Sheets, Pivot Tables, Data Cleaning, Data Visualization Skills: Data Analysis, Revenue Forecasting, Business Intelligence, Decision Support
Project Overview
This project analyzes the Manhattan vacation rental market to identify the most profitable property investment opportunities. The objective was to evaluate which neighborhoods and property sizes generate the highest demand and revenue, and to provide data-driven recommendations for investors seeking to maximize returns in the short-term rental market.
Using Airbnb listing and calendar datasets, I performed data cleaning, exploratory analysis, and revenue estimation to determine the most attractive rental segments. Reviews from the last 12 months were used as a proxy for rental demand, while nightly pricing data was used to estimate annual revenue potential.

Business Problem
Real estate investors needed guidance on where to invest in Manhattan vacation rentals. Specifically, they wanted to understand:
	•	Which neighborhoods have the highest rental demand
	•	What property sizes are most popular among guests
	•	How much revenue top-performing listings generate
	•	Which property types provide the best investment opportunity
The analysis focused on identifying high-demand locations and estimating potential annual earnings to support strategic investment decisions.

Data Sources
Listings Dataset
	•	Neighborhood
	•	Number of bedrooms
	•	Listing ID
	•	Number of reviews (last 12 months)
Calendar Dataset
	•	Listing ID
	•	Availability status
	•	Adjusted nightly price

Data Cleaning & Preparation
Several data quality issues were identified and resolved before analysis:
	•	Standardized neighborhood names by removing extra spaces and inconsistent capitalization
	•	Created a cleaned neighborhood field (neighborhood_clean)
	•	Replaced missing bedroom values with zero to correctly identify studio apartments
	•	Created a cleaned bedroom field (bedrooms_clean)
	•	Documented all transformations in a change log
	•	Preserved the original dataset as a raw data backup
These steps ensured consistency, accuracy, and reproducibility of the analysis.

Methodology
1. Identify High-Demand Neighborhoods
A pivot table was created using:
	•	Rows: Neighborhood
	•	Values: Number of reviews in the last 12 months
Reviews were used as a proxy for rental frequency to determine demand.
Top-performing neighborhoods included:
	•	Harlem
	•	Hell's Kitchen
	•	Lower East Side
A bar chart visualization was created to compare demand across the top 10 neighborhoods.

2. Determine Most Popular Property Sizes
A second pivot table analyzed the distribution of bedroom counts to identify the most common property sizes.
Key Findings:
	•	1-bedroom units were the most popular property type
	•	Studios were the second most common
	•	2-bedroom units ranked third
This pattern was consistent across most high-demand neighborhoods.

3. Revenue Estimation
Revenue was calculated using daily rental pricing data.
Steps performed:
	•	Created a revenue_earned column in the calendar dataset
	•	Used conditional logic to record revenue only when properties were rented
	•	Aggregated revenue using the SUMIF function
	•	Estimated annual revenue by multiplying 30-day revenue by 12
	•	Filtered listings to include only recommended property types
This allowed ranking listings based on financial performance.

Key Insights
	•	High-demand neighborhoods consistently showed strong rental activity
	•	1-bedroom units generated the highest demand across most locations
	•	Studio apartments were most popular in Midtown
	•	Top-performing listings demonstrated strong annual revenue potential
	•	Demand patterns were consistent enough to support targeted investment strategies

Business Recommendations
Based on the analysis, the following investment strategy is recommended:
	•	Invest in 1-bedroom properties in high-demand neighborhoods
	•	Consider studio apartments specifically in Midtown
	•	Focus on neighborhoods with high review activity as an indicator of demand
	•	Prioritize listings with strong short-term revenue performance
These recommendations help investors reduce risk and maximize return on investment.

Project Outcome
This analysis provided investors with a clear, data-driven framework for selecting profitable vacation rental properties. By combining demand analysis with revenue forecasting, the project translated raw data into actionable investment insights.
The final deliverable included:
	•	Cleaned and structured datasets
	•	Pivot table analysis
	•	Revenue calculations
	•	Data visualizations
	•	Executive summary with recommendations

Optional Section (Very Strong for Portfolios)
Skills Demonstrated
Technical Skills
	•	Data Cleaning
	•	Pivot Tables
	•	Data Aggregation
	•	Spreadsheet Modeling
	•	Revenue Forecasting
	•	Data Visualization
	•	Excel / Google Sheets
Business Skills
	•	Market Analysis
	•	Investment Decision Support
	•	KPI Analysis
	•	Stakeholder Reporting
	•	Problem Solving
