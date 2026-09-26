# Retail Sales Analytics Dashboard

An interactive Power BI dashboard built to analyze retail sales performance, customer behavior, product performance, and transaction cancellations using the UCI Online Retail II dataset.

## 📊 Dashboard Preview

### Retail Sales Analytics
![Retail Sales Analytics](screenshots/page1-sales-dashboard.png)

### Customer Analysis
![Customer Analysis](screenshots/page2-customer-analysis.png)

### Product & Returns Analysis
![Product & Returns Analysis](screenshots/page3-product-returns.png)

## 🎯 Project Objectives

- Analyze overall retail sales performance
- Track sales trends over time
- Identify top-performing countries
- Identify top products by sales and quantity
- Analyze high-value customers
- Analyze customers with the highest number of orders
- Examine sales and cancellation transactions
- Build an interactive business intelligence dashboard

## 🛠️ Technologies Used

- Power BI
- Power Query
- DAX
- Microsoft Excel
- Data Visualization
- Data Cleaning & Transformation

## 📂 Dataset

This project uses the **Online Retail II** dataset from the UCI Machine Learning Repository.

- **Dataset:** Online Retail II
- **Transactions:** 1,067,371
- **Period:** December 2009 – December 2011
- **Domain:** Online retail / e-commerce
- **Source:** UCI Machine Learning Repository

[View the Online Retail II dataset](https://archive.ics.uci.edu/dataset/502/online%2Bretail%2Bii)

## 🔄 Data Preparation

The data was prepared using Power Query.

Main transformations included:

- Combined the 2009–2010 and 2010–2011 datasets
- Converted Invoice to text
- Identified sales and cancellation transactions
- Created Sales Amount
- Extracted invoice date
- Created Year, Month Number and Month Name
- Filtered invalid/non-positive prices
- Checked missing values
- Preserved valid transaction records for analysis

## 📈 Dashboard Pages

### 1. Retail Sales Analytics

Provides an overall view of:

- Total Sales
- Total Orders
- Total Customers
- Total Products
- Monthly Sales Trend
- Sales by Country
- Top Products by Quantity

Interactive filters are available for:

- Year
- Country
- Transaction Type

### 2. Customer Analysis

Analyzes customer purchasing behavior through:

- Top 10 Customers by Sales
- Top 10 Customers by Orders

### 3. Product & Returns Analysis

Analyzes:

- Top 10 Products by Sales
- Product Quantity vs Sales
- Sales vs Cancellations

## 🔍 Key Skills Demonstrated

- Data cleaning
- Data transformation
- Data modeling
- Interactive dashboard development
- Business-oriented data visualization
- Customer analysis
- Product analysis
- Time-series analysis
- Power BI reporting

## 📌 Key Insights

The dashboard enables analysis of:

- Overall sales performance across the complete transaction period
- Monthly sales trends and changes over time
- Countries contributing to sales
- Products generating the highest sales and quantities
- Customers generating the highest sales
- Customers placing the highest number of orders
- Differences between sales and cancellation transactions

The dashboard is interactive, allowing users to filter the analysis by year, country, and transaction type.


## 🔄 Project Workflow

```text
Raw Retail Data
      ↓
Power Query
      ↓
Data Cleaning & Transformation
      ↓
Data Modeling
      ↓
Power BI Visualizations
      ↓
Interactive Dashboard
      ↓
Business Insights
## 📁 Project Structure

```text
Retail-Sales-Analytics-Dashboard/
│
├── Retail_Sales_Analytics_Dashboard.pbix
├── screenshots/
│   ├── page1-sales-dashboard.png
│   ├── page2-customer-analysis.png
│   └── page3-product-returns.png
│
└── README.md
