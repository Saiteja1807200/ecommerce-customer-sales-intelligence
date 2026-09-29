# E-Commerce Customer & Sales Intelligence Platform

A data analytics and business intelligence project that analyzes e-commerce transactions to uncover revenue trends,customer behavior,product performance,and customer segments using Python,Pandas,SQL,and Power BI.

## Dashboard Preview

### Sales & Customer Insights

![Monthly Revenue Trend](images/monthly_revenue_trend.png)

### Customer Analysis

![Customer Segments](images/customer_segments.png)

![Revenue by Customer Segment](images/revenue_by_customer_segment.png)

---

## Project Overview

This project transforms raw e-commerce transaction data into actionable business insights.

The analysis covers:

- Revenue and order performance
- Monthly sales trends
- Product performance
- Country-level revenue
- Customer purchasing behavior
- Repeat customer analysis
- Customer lifetime value indicators
- RFM-based customer segmentation
- Interactive Power BI dashboards

The project demonstrates an end-to-end analytics workflow starting from raw transactional data and ending with a business intelligence dashboard.

---

## Business Objectives

The main objectives of this project are to:

1. Understand overall sales and revenue performance.
2. Identify high-performing products and markets.
3. Analyze customer purchasing frequency and spending behavior.
4. Identify high-value and at-risk customer segments.
5. Build an interactive dashboard for business decision-making.
6. Create a reproducible data-cleaning and analysis workflow.

---

## Dataset

The project uses the **Online Retail** dataset containing transactional data from a UK-based online retailer.

The dataset contains approximately **541,909 original transactions** and includes fields such as:

| Column | Description |
|---|---|
| InvoiceNo | Transaction/invoice number |
| StockCode | Product code |
| Description | Product description |
| Quantity | Number of units purchased |
| InvoiceDate | Transaction date and time |
| UnitPrice | Price per unit |
| CustomerID | Unique customer identifier |
| Country | Customer country |

The original dataset is not included in the GitHub repository because of its size.

Dataset source:

**UCI Machine Learning Repository — Online Retail Dataset**

---

## Technology Stack

### Programming & Data Analysis

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

### Database & Querying

- SQL
- PostgreSQL

### Business Intelligence

- Microsoft Power BI
- Power Query
- DAX
- Data Modeling

### Development Tools

- VS Code
- Git
- GitHub

---

## Project Workflow

```text
Raw Transaction Data
        |
        v
Data Quality Analysis
        |
        v
Data Cleaning
        |
        v
Exploratory Data Analysis
        |
        +------------------+
        |                  |
        v                  v
Sales Analysis       Customer Analysis
        |                  |
        |                  v
        |            RFM Segmentation
        |                  |
        +---------+--------+
                  |
                  v
          Power BI Dashboard
                  |
                  v
        Business Insights
