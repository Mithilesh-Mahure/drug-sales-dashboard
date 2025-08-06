🩺 Drug Sales Dashboard

<img width="959" height="541" alt="image" src="https://github.com/user-attachments/assets/41866f82-0eb8-4f92-b321-b6a21fce980e" />

Table of Contents
Project Overview

Problem Statement

Dataset Description

Solution & Approach

Dashboard Features

Usage Instructions

Key Insights & Findings

Recommendations

Tech Stack

Getting Started

License

Contact

1. Project Overview
A comprehensive, interactive Power BI dashboard designed to analyze drug sales data, enabling stakeholders to visualize key metrics, demographic breakdowns, and trends over time to support strategic decisions.

2. Problem Statement
Stakeholders requested visibility into pharmaceutical sales performance by drug, geography, customer demographics, and time—aiming to uncover top-performing products, sales channels, customer trends, and seasonality.

3. Dataset Description
Typically includes three CSV files:

Customers.csv – Customer demographics (CustomerID, Age, Gender, Country, etc.)

Drugs.csv – Product info (DrugID, DrugName, UnitPrice, Cost, Treats, etc.)

Sales.csv – Transactions (SaleID, DrugID, CustomerID, UnitsSold, SaleDate, BuyerType, etc.)

4. Solution & Approach
Load and clean data using Power Query Editor (remove duplicates, correct types).

Build a star schema data model in Power BI linking lookup tables (Customers, Drugs) to the fact table (Sales).

Create interactive visuals and slicers for time (year/quarter/month).

5. Dashboard Features
Page 1: Overview
KPIs: Total sales quantity, total revenue, total cost, profit

Top/Bottom Drugs & Customers: Bar charts by revenue, profit, units sold

Trend Charts: Revenue by year, quarter, month

Page 2: Customer & Demographics
Map of sales by country

Revenue by Gender (pie/doughnut chart)

Revenue by Age Group (bar chart)

Revenue by Buyer Type

Page 3: Time-Series Trends
Year-over-year growth

Monthly and weekly revenue trends

Day-of-week sales patterns

6. Usage Instructions
If you have Power BI Desktop, open the .pbix file directly (datasets embedded).

Otherwise, access the Power BI Service link (if published).

Use slicers to filter by year, month, drug, buyer type, etc.
