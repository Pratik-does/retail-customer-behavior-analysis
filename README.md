# Retail Customer Behavior Analysis

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

## Overview

This project analyzes retail customer shopping behavior to identify what drives revenue, repeat purchases, and customer engagement.  
It combines Python, SQL, PostgreSQL, and Power BI to turn raw customer data into clear business insights.

The final project includes data preparation, SQL-based analysis, an interactive dashboard, and a business report.

## Business Problem

A retail company wants to better understand customer behavior across product categories, demographics, subscription status, discounts, and shipping choices.

The main question is:

> How can customer shopping data be used to identify trends, improve customer engagement, and optimize marketing and product strategy?

## Project Objective

The goal of this project is to find:

- the main revenue drivers
- the strongest customer segments
- product category performance
- the impact of subscription status
- shipping and discount patterns
- demographic trends in revenue and spending

## Tools Used

- Python
- Pandas
- SQL
- PostgreSQL
- Power BI
- Jupyter Notebook

## Workflow

1. Collected the raw dataset  
2. Cleaned and prepared the data in Python  
3. Stored the cleaned data in PostgreSQL  
4. Wrote SQL queries to answer business questions  
5. Built an interactive Power BI dashboard  
6. Prepared a report and presentation with findings and recommendations

## Key Findings

- Clothing is the top revenue-generating category
- Male customers contribute more revenue than female customers
- Young and middle-aged customers are the strongest revenue groups
- Loyal customers make up the largest share of the customer base
- Subscription status does not significantly change average spend
- Discount usage and shipping type both influence buying behavior

## Dashboard Highlights

The Power BI dashboard includes:

- total customers
- average purchase amount
- average review rating
- subscription split
- revenue by category
- sales by category
- revenue by age group
- sales by age group
- interactive slicers for deeper analysis

## SQL Analysis

The SQL analysis includes queries for:

- revenue by gender
- customer segmentation into New, Returning, and Loyal
- subscription comparison
- top products by category
- revenue by age group
- shipping comparison
- discount behavior
- repeat buyer analysis

## Business Recommendations

Based on the analysis, the company should:

- improve the value of the subscription program
- focus more on the Clothing category
- target Male, Young, and Middle-aged customers
- use discounts more selectively
- strengthen loyalty-based marketing
- review shipping strategy to support customer satisfaction

## Repository Structure

```bash
retail-customer-behavior-analysis/
├─ data/
│  ├─ raw/
│  │  └─ customer_shopping_behavior.csv
│  └─ processed/
│     └─ cleaned_data.csv
├─ sql/
│  └─ customer_behavior_analysis.sql
├─ notebooks/
│  └─ Data_Exploration.ipynb
├─ dashboard/
│  └─ Customer_Behavior_Analysis_Dashboard.pbix
├─ presentation/
│  └─ Retail_Customer_Behavior_Analysis.pptx
├─ report/
│  └─ Retail_Customer_Behavior_Analysis_Report.pdf
├─ screenshots/
│  ├─ dashboard_overview.png
│  ├─ dashboard_subscription_yes.png
│  ├─ dashboard_subscription_no.png
│  ├─ dashboard_clothing_filter.png
│  ├─ dashboard_shipping_filter.png
│  ├─ sql_customer_segmentation.png
│  ├─ sql_subscription_comparison.png
│  ├─ sql_revenue_by_gender.png
│  ├─ sql_revenue_by_age_group.png
│  └─ Retail_Customer_Behavior_Insights_Map.png
└─ README.md
