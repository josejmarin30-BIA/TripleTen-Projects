📊 Venture Capital Investment Database Analysis (SQL Project)

Author: Jose Marin
Role: Data Analyst
Tools: SQL | Relational Databases | Data Analysis
Skills: SQL Queries, Data Aggregation, Joins, CASE Statements, Business Intelligence, Investment Analysis

📌 Project Overview

This project analyzes a relational database containing information about venture funds, startups, acquisitions, and industry professionals. The objective was to generate insights that support venture capital firms in making data-driven investment decisions.

Using SQL, I performed data exploration, filtering, aggregation, and joins to evaluate startup success rates, funding patterns, acquisition behavior, and investor activity levels. The analysis helped identify investment trends, geographic funding distribution, and potential partnership opportunities across the venture capital ecosystem.

🎯 Business Problem

Venture capital firms rely on data to guide multi-million dollar investment decisions. The executive team needed insights into startup performance, funding behavior, and investment activity to support their quarterly investment strategy.

This project focused on answering key business questions such as:

How many companies have closed down versus remained active
How much funding specific industries have raised
What acquisition trends occurred during economic recovery periods
Which countries attract the most venture capital funding
How fund activity levels influence investment strategies
Whether employee education levels correlate with startup success
🗄️ Database Structure

The database contains multiple related tables tracking venture capital activity.

Key Tables Used

company
acquisition
fund
funding_round
people
education

These tables were connected using relational keys to support multi-table analysis.

🔎 Analysis Tasks
1. Startup Landscape Analysis

Objective:
Determine the number of companies that have closed down to establish a baseline startup success rate.

SQL Concepts Used:

SELECT
COUNT
WHERE
2. Sector Analysis for US Investors

Objective:
Analyze total funding raised by news-related companies in the United States to benchmark investment levels.

SQL Concepts Used:

WHERE with multiple conditions
ORDER BY
Filtering
3. Cash Acquisition Trends

Objective:
Identify total cash-based acquisitions between 2011 and 2013 to understand post-recession acquisition behavior.

SQL Concepts Used:

SUM
WHERE
Date filtering
4. Identifying Industry Influencers

Objective:
Find individuals whose Twitter usernames begin with "Silver" for targeted marketing outreach.

SQL Concepts Used:

LIKE
Pattern matching
5. Finding Finance Influencers

Objective:
Identify finance-focused influencers whose Twitter usernames contain "money" and whose last names start with "K".

SQL Concepts Used:

LIKE
Logical operators (AND)
6. Geographic Investment Analysis

Objective:
Determine which countries attract the most venture capital funding.

SQL Concepts Used:

GROUP BY
SUM
ORDER BY
7. Funding Round Volatility Analysis

Objective:
Identify dates with significant variation between minimum and maximum funding amounts.

SQL Concepts Used:

GROUP BY
MIN and MAX
HAVING
8. Fund Activity Classification

Objective:
Categorize venture funds based on investment activity levels.

Categories Created:

high_activity — 100 or more investments
middle_activity — 20 to 99 investments
low_activity — fewer than 20 investments

SQL Concepts Used:

CASE
Conditional logic
9. Investment Strategy by Fund Activity

Objective:
Analyze how funding behavior differs across fund activity levels.

SQL Concepts Used:

CASE
GROUP BY
AVG
ORDER BY
10. Employee Education Impact on Startup Success

Objective:
Analyze whether employee education levels correlate with startup failure.

SQL Concepts Used:

JOIN
GROUP BY
AVG
Filtering
📈 Key Insights
Startup closures provided a baseline measure of risk in the venture capital ecosystem
News-related companies in the United States received significant funding compared to other sectors
Cash acquisitions increased during the economic recovery period
Certain countries consistently attracted higher levels of venture capital investment
High-activity funds participated in more funding rounds on average
Failed startups often had limited funding rounds
💡 Business Recommendations

Based on the analysis, the following recommendations were provided:

Monitor startup closure rates to assess investment risk
Benchmark funding levels within target industries before investing
Evaluate acquisition payment methods to understand market trends
Focus investment strategies on high-performing geographic regions
Partner with highly active venture funds for broader investment opportunities
Consider funding history alongside workforce characteristics when evaluating startups
🛠️ Skills Demonstrated
Technical Skills (Hard Skills)
SQL Query Writing
Data Filtering
Data Aggregation
GROUP BY and HAVING
JOIN Operations
CASE Statements
Pattern Matching
Relational Database Analysis
Business Intelligence Reporting
Data Analysis
Professional Skills (Soft Skills)
Analytical Thinking
Problem Solving
Attention to Detail
Business Decision Support
Data Interpretation
Communication of Insights
Stakeholder Reporting
Critical Thinking
📂 Repository Structure
venture-capital-sql-analysis/
│
├── sql_queries/
│   └── analysis_queries.sql
│
├── data/
│   └── database_schema.png
│
├── documentation/
│   └── project_summary.md
│
└── README.md
🚀 Project Outcome

This project demonstrates the ability to use SQL to analyze complex relational databases and generate insights that support venture capital investment decisions. The analysis translated raw data into actionable recommendations for investors and stakeholders.
