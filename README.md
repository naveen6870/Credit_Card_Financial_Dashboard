Credit Card Financial Analytics Dashboard
📌 Project Overview

This project focuses on analyzing credit card transaction and customer data to uncover revenue drivers, activation patterns, and portfolio performance trends. An interactive Power BI dashboard was built using SQL-driven data to support data-driven decision-making and simulate business growth strategies in a financial services context.

The objective is to provide stakeholders with actionable insights to optimize card performance, improve customer activation, and drive revenue growth.

🎯 Business Objective

Identify key revenue drivers across card segments

Analyze customer activation patterns and usage behavior

Evaluate portfolio performance to support strategic business decisions

Enable leadership to take data-backed actions for business growth

🗂️ Data Description

The project uses two primary datasets:

1. Credit Card Transactions Dataset

Transaction ID

Transaction Date

Card Category (Blue, Silver, Gold, Platinum)

Transaction Amount

Revenue

Transaction Count

2. Customer Dataset

Customer ID

Card Category

Activation Status

Demographics (Age Group, Income Group, etc.)

These datasets were joined and aggregated using SQL to create analytical views for dashboarding.

🛠️ Tools & Technologies

SQL – Data extraction, joins, aggregations, KPI calculations

Power BI – Data modeling, DAX measures, interactive dashboards

Power Query – Data cleaning and transformation

Excel – Initial data exploration and validation

🔄 Workflow / Methodology

Data Collection & Understanding
Reviewed transaction and customer datasets to understand structure and business context.

Data Cleaning & Transformation

Removed duplicates and null values

Standardized formats (dates, categories)

Created calculated fields using Power Query

SQL Data Processing

Joined transaction and customer tables

Aggregated revenue, transaction count, and activation metrics

Created analytical views for dashboard consumption

Data Modeling in Power BI

Built relationships between tables

Created calculated measures using DAX

Designed a star schema for performance

Dashboard Development

Designed interactive visuals for KPI tracking

Added slicers for dynamic analysis

Focused on executive-level readability

Insight Generation & Business Interpretation
Interpreted trends and converted them into actionable business insights.

📊 Key Business Insights

Blue & Silver cards contribute ~93% of total transactions, indicating strong performance in mass market segments.

Revenue increased by 28.8%, highlighting positive portfolio growth.

Activation rate is 57.5%, suggesting significant scope to improve onboarding and engagement strategies.

Certain card categories show lower activation but higher average revenue, indicating opportunities for targeted marketing.

These insights can be leveraged to:

Optimize marketing campaigns

Improve customer onboarding strategies

Enhance portfolio profitability

📈 Dashboard Highlights

The Power BI dashboard provides:

KPI Cards: Total Revenue, Total Transactions, Activation Rate

Card Category Analysis: Revenue & transaction contribution by card type

Trend Analysis: Revenue and transaction growth over time

Customer Insights: Activation patterns and segment performance

Interactive Filters: Card type, time period, customer segment

(Add screenshots of your dashboard here for maximum impact)

🚀 How to Run / Explore the Project

Download and install Power BI Desktop

Clone or download this repository

Open the file:
Credit_Card_Financial Dashboard.pbix

Ensure the dataset files are in the same directory or update data source paths

Refresh the data and explore the interactive dashboard

📁 Repository Structure
Credit_Card_Financial_Dashboard/
│
├── Credit_Card_Financial Dashboard.pbix
├── Credit_Card_Dashboard.pdf
├── SQL_Query.sql
├── Dataset/
│   ├── credit_card.csv
│   └── customer.csv
└── README.md

💡 Business Value

This project demonstrates the ability to:

Perform data-driven decision making

Apply strategic analytics in a financial services environment

Translate raw data into actionable business insights

Build executive-ready dashboards for stakeholder consumption

👤 Author

Naiko Naveen
Data Analyst | SQL | Python | Power BI
LinkedIn: [Add your LinkedIn link]
GitHub: https://github.com/naveen6870

Important (Please Do This)

Once you paste this README:

Add 2–3 screenshots of your Power BI dashboard under “Dashboard Highlights”

Make sure your SQL file is clean and readable

Check that your pbix file opens without issues
