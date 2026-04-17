🏬 Saving SuperStore: Profitability, Advertising, and Returns Analysis

Author: Jose Marin
Role: Data Analyst / Business Intelligence Analyst
Tools Used: Tableau | Excel | Data Visualization | Data Analysis
Skills: Profitability Analysis, Business Intelligence, Data Visualization, ROI Analysis, Customer Behavior Analysis

📌 Project Overview

The SuperStore business faced declining profitability and risk of financial loss. As a data analyst consultant, I was tasked with reviewing operational data to identify profit drivers, loss sources, advertising opportunities, and return-related risks.

This project focused on transforming transactional sales and returns data into actionable insights using data visualization and business analytics techniques. The analysis provided recommendations on which products to discontinue, which product categories to prioritize, where to invest in advertising, and how product returns impact profitability.

🎯 Business Problem

The SuperStore needed data-driven recommendations to improve financial performance and avoid potential bankruptcy. Leadership required clear insights into operational inefficiencies and opportunities for revenue growth.

Key business questions included:

Where are the biggest sources of profit and loss?
Which products should be discontinued?
Which product categories should be prioritized?
Where and when should the company invest in advertising?
Which products and customers have the highest return rates?
How do returns impact profitability?
🗂️ Dataset Description

The dataset includes retail transaction and return data from a SuperStore operation.

Tables Used
Orders Table
Column	Description
Order ID	Unique identifier for each order
Order Date	Date the order was placed
Ship Mode	Shipping method used
Customer Name	Customer identifier
State	Customer location
Category	Product category
Sub-Category	Product classification
Product Name	Item purchased
Sales	Total sales amount
Profit	Profit generated from the sale
Returns Table
Column	Description
Order ID	Unique identifier for returned order
Returned	Indicates if the product was returned
📊 Project Tasks & Analysis
Part 1: Profit & Loss Analysis

The first stage of the analysis focused on identifying key profit centers and loss drivers across product and geographic dimensions.

Objectives
Identify the two biggest profit centers
Identify the two biggest loss-makers
Determine which products should be discontinued
Identify high-performing and low-performing subcategories
Methods
Aggregated profit across combinations of dimensions
Compared profitability across product categories and regions
Identified consistently negative-performing products
Used visualizations to highlight performance differences
Outcome

The analysis identified specific products and subcategories generating consistent losses, allowing leadership to make informed decisions about inventory management and product strategy.

Part 2: Advertising Analysis

This stage evaluated whether targeted advertising investments would generate sufficient returns based on historical profit patterns.

Objectives
Identify the three best state and month combinations for advertising
Determine potential return on advertising investment
Estimate recommended advertising spending
Business Rule

The company should spend up to:

20% of profit on advertising

Methods
Calculated average monthly profit by state
Compared seasonal profit patterns
Identified high-performing geographic markets
Estimated advertising budget based on profit
Outcome

The analysis identified high-value geographic and seasonal opportunities where advertising investment would likely produce the strongest financial returns.

Part 3: Returns Analysis

The final stage focused on understanding the impact of product returns on profitability and operational efficiency.

Objectives
Identify products with the highest return rates
Identify customers with the highest return rates
Evaluate the relationship between return rates and profitability
Recommend whether to continue or limit operations based on return behavior
Methods
Joined Orders and Returns datasets using a LEFT JOIN
Created a calculated return indicator field
Calculated return rates across products and customers
Compared average profit against return rate
Key Metric

Return Rate = Returned Orders ÷ Total Orders

Outcome

The analysis revealed products and customers with unusually high return behavior, providing evidence to support risk mitigation and operational improvement strategies.

📈 Key Insights
Certain product and regional combinations generated the highest profits
Some products consistently produced negative profit margins
High-performing product categories contributed significantly to revenue
Specific states and months demonstrated strong advertising potential
Elevated return rates were associated with reduced profitability
Targeted operational changes could improve financial performance
💡 Business Recommendations

Based on the analysis, the following recommendations were provided:

Discontinue consistently unprofitable products
Focus inventory and marketing on high-performing subcategories
Invest in targeted advertising during high-profit periods
Monitor return behavior to reduce operational losses
Use profitability metrics to guide strategic decision-making
🛠️ Skills Demonstrated
Hard Skills (Technical Skills)
Data Visualization
Tableau / Business Intelligence Tools
Data Cleaning and Preparation
Profitability Analysis
Return Rate Analysis
Trend Analysis
Data Aggregation
Calculated Fields
LEFT JOIN Data Integration
Dashboard Development
KPI Development
ROI Analysis
Soft Skills (Professional Skills)
Analytical Thinking
Problem Solving
Business Decision Support
Attention to Detail
Critical Thinking
Data Interpretation
Communication of Insights
Stakeholder Reporting
Strategic Planning
📂 Repository Structure
saving-superstore-analysis/
│
├── data/
│   ├── orders_dataset.xlsx
│   └── returns_dataset.xlsx
│
├── dashboards/
│   ├── profit_loss_analysis.twbx
│   ├── advertising_analysis.twbx
│   └── returns_analysis.twbx
│
├── visuals/
│   ├── profit_centers.png
│   ├── loss_makers.png
│   ├── advertising_opportunities.png
│   └── return_rate_analysis.png
│
└── README.md
🚀 Project Outcome

This project demonstrates the ability to analyze retail performance data, identify operational risks, and provide data-driven business recommendations. The analysis supported strategic decisions aimed at improving profitability, optimizing marketing investments, and reducing losses caused by product returns.
