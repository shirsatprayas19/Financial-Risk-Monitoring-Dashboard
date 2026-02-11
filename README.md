# Financial-Risk-Monitoring-Dashboard
End-to-end financial risk analytics project using SQL and Power BI to identify high-risk entities and uncover key drivers like profit margin, debt ratio, and market volatility.

-- Project Overview

This project presents an end-to-end Financial Risk Monitoring solution built using SQL Server (SSMS) and Power BI.The objective was to analyze corporate financial data and identify high-risk entities using key financial and operational metrics such as:
Profit Margin
Debt Ratio
Liquidity Ratio
Revenue
Operating Cost
Cash Flow
Market Volatility Index
Transaction Volume

The dashboard provides an executive-level view to support risk management and strategic decision-making.

-- Business Objective

To identify financially stressed entities and analyze the key drivers contributing to corporate risk classification.
The dashboard answers questions such as:
1)What percentage of entities fall under high risk?
2)How does profitability vary across risk classes?
3)Do higher debt levels correlate with increased risk?
4)How does liquidity impact financial stability?
5)What role does market volatility play in risk exposure?

-- Tech Stack

SQL Server (SSMS) – Data cleaning, aggregation, and view creation
Power BI – Data modeling, DAX measures, dashboard development
DAX – KPI calculations and risk metrics

-- Data Processing Steps

1️)Data Import
Imported CSV dataset into SQL Server.
Cleaned null values and adjusted column formats.
2️)Data Modeling in SQL
Created structured table:
financial_risk_monitoring_clean_dataset
Built analytical SQL views to compute:
Average Profit Margin,Average Debt Ratio,Liquidity Ratio,Revenue and Cost summaries,Risk classification breakdown
3️)Power BI Development
Connected Power BI to SQL Server view.
Created DAX measures:
Total Entities
High Risk %
Avg Profit Margin
Avg Debt Ratio
Avg Liquidity Ratio

Designed interactive dashboard with slicers and KPIs.

-- Dashboard Structure
Executive Risk Overview -
Total Entities
High Risk %
Avg Profit Margin
Avg Debt Ratio
Avg Liquidity Ratio
Risk distribution visualization

Financial Drivers -
Revenue vs Risk Class
Operating Cost vs Risk Class
Cash Flow analysis
Market Volatility impact
Transaction and Management activity metrics

-- Key Insights

~20% of entities fall under the High-Risk category.
Higher risk entities tend to show reduced revenue and weaker cash flow.
Debt ratio increases across higher risk segments.
Liquidity coverage slightly decreases with rising risk levels.
Market volatility and management activity show correlation with risk classification.

-- Sample KPIs 

Metric	Value
Total Entities - 1500
High Risk % -	20.33%
Avg Profit Margin -	64.15%
Avg Debt Ratio - 0.49
Avg Liquidity Ratio	- 1.95

-- What This Project Demonstrates

SQL data modeling & aggregation
Financial KPI analysis
Business-oriented dashboard design
DAX measure creation
Risk segmentation analysis
Executive storytelling using data



