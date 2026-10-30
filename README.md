# Retail Business Performance Dashboard | Power BI

## Project Overview

This project focuses on analyzing retail business performance using Microsoft Power BI. The objective is to transform raw retail data into meaningful business insights through data cleaning, data modeling, DAX calculations, and interactive dashboards.

The dashboard helps management understand sales performance, profitability, customer contribution, product performance, regional performance, and shipping efficiency.

## Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Modeling

## Dataset

The project uses a retail dataset containing order, customer, product, sales, profit, discount, location, and shipping information.

The dataset includes intentionally introduced data-quality issues for practical data-cleaning experience.

## Data Cleaning & Preparation

Data preparation was performed using Power Query.

Key cleaning and validation activities included:

- Duplicate record identification and removal.
- Handling missing values.
- Standardizing inconsistent text values.
- Validating date fields.
- Identifying invalid discount values.
- Identifying zero quantities.
- Separating negative sales and negative profit for investigation.
- Creating data-quality status columns.

## Data Modeling

A Star Schema data model was implemented.

- Fact_Sales
- Dim_Date
- Dim_Customer
- Dim_Product
- Dim_Location

Relationships were established between the fact and dimension tables to support accurate filtering and analysis.

## DAX & Business Metrics

Key measures developed include:

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Average Order Value (AOV)
- Profit Margin %
- Previous Month Sales
- Sales Growth %
- Average Shipping Days
- Customer Sales Contribution %

## Dashboard Pages

### 1. Executive Dashboard

Provides a high-level overview of business performance.

- Total Sales
- Total Profit
- Total Orders
- Total Customers
- Profit Margin
- Average Order Value
- Monthly Sales Trend
- Regional Performance
- Category Sales

### 2. Product & Customer Analysis

Focuses on product performance and customer profitability.

- Top 10 Products by Sales
- Top 10 Products by Profit
- Customer Contribution
- Customer Profitability
- Product Sales vs Profitability

### 3. Regional & Shipping Analysis

Evaluates regional performance and shipping efficiency.

- Regional Sales & Profitability
- Average Shipping Time by Ship Mode
- Shipping Mode Performance

## Interactive Features

- Date slicer
- Region slicer
- Category slicer
- Ship Mode slicer
- Dynamic dashboard title
- Cross-filtering between visuals
- Conditional formatting
- Page navigation

## Project Objectives

- Understand overall retail business performance.
- Identify profitable and loss-making products.
- Analyze customer contribution and profitability.
- Compare regional performance.
- Evaluate shipping efficiency.
- Support data-driven business decisions.

## Repository Structure

```text
Retail-Business-Performance-Dashboard/
│
├── Dataset/
│   └── PowerBI_Project1_Retail_Messy.xlsx
│
├── Screenshots/
│   ├── Executive_Dashboard.png
│   ├── Product_Customer.png
│   └── Regional_Shipping.png
│
└── README.md
```

## Author

Data Analytics Portfolio Project

**Tools:** Power BI | Power Query | DAX | Excel
