# Tailwinds-Sales-PowerBi-Analysis


# 📊 Tailwind Traders Business Intelligence Dashboard | Power BI, Excel & DAX

## Project Overview

This project demonstrates the end-to-end development of an interactive Business Intelligence dashboard for **Tailwind Traders** using **Power BI, Microsoft Excel, Power Query, DAX, and Python**.

The objective was to transform raw sales, purchasing, and country data into a centralized reporting solution that enables stakeholders to monitor sales performance, profitability, customer activity, and operational trends through interactive visualizations.

The project follows the complete Business Intelligence lifecycle, including data preparation, ETL, data modeling, DAX development, performance optimization, and dashboard design.

---

# Business Problem

Tailwind Traders required a reporting solution capable of:

- Monitoring company sales performance
- Tracking profitability across products and countries
- Comparing revenue and profit trends over time
- Identifying high and low performing markets
- Providing interactive reporting for business decision-making

---

# Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- Power Query
- DAX (Data Analysis Expressions)
- Python (Pandas)
- Data Modeling
- Star Schema Design

---

# Dataset

The project integrates multiple data sources including:

- Sales Transactions
- Purchase Records
- Country Information
- Currency Exchange Rates

These datasets were combined to create a complete reporting model capable of analyzing both operational and financial performance.

---

# Data Preparation

The source data was first prepared in Microsoft Excel by creating additional calculated fields required for reporting.

New calculations included:

- Gross Revenue
- Total Tax
- Net Revenue
- Profit

The datasets were then imported into Power BI where Power Query was used to:

- Validate data types
- Standardize columns
- Remove unnecessary records
- Filter returned purchases
- Prepare the data for modeling

---

# Python Integration

Historical currency exchange rates were imported using a Python script with the Pandas library.

This created an additional Exchange Data table used to convert financial metrics into a common reporting currency.

---

# Data Modeling

A relational data model was created linking:

- Sales
- Purchases
- Countries
- Exchange Rates
- Calendar Table

The model follows a structured approach that supports efficient filtering, accurate calculations, and scalable reporting.

A custom Calendar table was also developed to enable advanced time intelligence calculations.

---

# DAX Measures Developed

Custom DAX calculations included:

- Yearly Profit Margin
- Quarterly Profit
- Year-to-Date (YTD) Profit
- Median Sales

Time intelligence functions such as:

- CALCULATE()
- TOTALYTD()
- DATESQTD()
- MEDIAN()

were implemented to support business reporting and trend analysis.

---

# Dashboard Features

The completed report includes two interactive dashboard pages:

## Sales Overview

Provides a high-level summary of sales activity including:

- Stock Levels
- Quantity Purchased
- Median Sales
- Loyalty Points by Country
- Quantity Sold by Product
- Median Sales Distribution
- Sales Trends Over Time

Interactive slicers allow users to filter results by country.

---

## Profit Overview

Focuses on company profitability through:

- Gross Revenue KPI
- Net Revenue
- Year-to-Date Profit
- Net Revenue by Product
- Profit Margin by Country
- Profit Trends Over Time

---

# Performance Optimization

Power BI Performance Analyzer was used to evaluate report efficiency and optimize DAX query performance, ensuring visuals loaded efficiently for end users.

---

# Key Skills Demonstrated

- Data Cleaning
- ETL
- Power Query
- Excel
- Python (Pandas)
- Data Modeling
- Relationship Management
- Star Schema Design
- DAX
- Time Intelligence
- KPI Development
- Dashboard Design
- Data Visualization
- Business Intelligence
- Performance Optimization

---

# Business Value

The completed dashboard enables decision-makers to:

- Monitor company sales performance
- Evaluate profitability across products and countries
- Analyze sales trends over time
- Compare regional performance
- Support strategic business decisions through interactive reporting

---

# Repository Contents

```
📁 Tailwind-Traders-PowerBI-Analysis
│
├── Tailwind Traders Dashboard.pbix
├── Sales.xlsx
├── Purchases.xlsx
├── Countries.xlsx
├── README.md
└── images
    ├── sales-overview.png
    ├── profit-overview.png
    ├── data-model.png
    └── performance-analyzer.png
```

---

# Dashboard Preview

## Sales Overview

*(Insert screenshot here)*

![Sales Overview](images/sales-overview.png)

---

## Profit Overview

*(Insert screenshot here)*

![Profit Overview](images/profit-overview.png)

---

## Data Model

*(Insert screenshot here)*

![Data Model](images/data-model.png)

---

# Author

**Daniel Cortese**

Aspiring Business Analyst | SQL | Power BI | Excel | Python | Data Analytics
