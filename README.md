# Sales Performance & Revenue Analytics Project
An end-to-end data analytics project designed to transform raw retail sales data into actionable business insights. The project simulates a real-world analytics workflow where data is cleaned, analyzed, and visualized to help stakeholders monitor performance and make data-driven decisions.

# Business Problem

Retail businesses often struggle with limited visibility into sales performance across regions, products, and time periods. Without structured analytics, it becomes difficult to identify revenue drivers, detect underperforming segments, or optimize inventory and marketing strategies.

The objective of this project is to build a data-driven sales intelligence system that helps answer key business questions such as:

Which products generate the highest revenue?

Which regions are underperforming?

What seasonal trends exist in sales?

How can businesses track KPIs for revenue growth?

# Dataset Overview

The dataset contains 50,000+ retail sales transactions including:

Order Date

Product Category

Sales Amount

Quantity

Region

Customer Segment

Profit / Revenue metrics

This dataset simulates a real retail business environment where transactional data is generated continuously.

Project Workflow

The analytics pipeline follows a structured workflow commonly used in industry.

1. # Data Ingestion

Raw sales data is loaded into Python for initial exploration and preprocessing.

2. # Data Cleaning & Transformation

Using Pandas, the dataset is cleaned by:

Handling missing values

Standardizing date formats

Removing duplicates

Creating derived features such as monthly sales trends

3. # Exploratory Data Analysis (EDA)

EDA was performed to understand business patterns including:

Revenue distribution

Product category performance

Region-wise sales contribution

Seasonal sales trends

4. # SQL Analytics Layer

The cleaned dataset was stored in MySQL, enabling structured queries to compute business KPIs such as:

Monthly revenue growth

Top-performing products

Region-wise revenue contribution

Profitability analysis

5. # Business Intelligence Dashboard

An interactive Power BI dashboard was created to visualize insights and help stakeholders monitor business performance.

The dashboard includes:

Revenue KPIs

Monthly sales trends

Top product categories

Regional performance comparison

Interactive filters for deeper analysis

# Key Insights

Some of the insights uncovered during the analysis include:

The top 20% of products contributed to ~65% of total revenue, indicating strong product concentration.

Certain regions showed 18% lower revenue growth, highlighting potential market expansion opportunities.

Sales exhibited clear seasonal spikes, suggesting opportunities for targeted promotions and inventory planning.

# Tech Stack

Python – Data cleaning and exploratory data analysis

Pandas – Data manipulation and preprocessing

MySQL – SQL-based analytics and KPI computation

Power BI – Interactive business intelligence dashboard

# Business Impact

This project demonstrates how raw transactional data can be converted into strategic insights that support:

Revenue monitoring

Product performance analysis

Regional sales optimization

Data-driven decision making

# Future Improvements

Possible enhancements to this project include:

Sales forecasting using machine learning

Customer segmentation models

Automated data pipelines

Deployment of dashboards for real-time analytics

# Author

Sukhad Tomar