# NeoStats Data Engineering Assessment

## Project Overview

This project demonstrates an end-to-end retail sales data engineering pipeline using Python, Pandas, and Power BI.

The solution includes:

* Data ingestion
* Data cleaning and validation
* Data transformation
* PII masking
* KPI generation
* Business intelligence dashboard creation

---

# Tools & Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook
* VS Code
* Power BI Desktop

---

# Project Structure

```text
Code/
│
├── retail_pipeline.ipynb

Data/
│
├── Raw/
├── Processed/
│   ├── cleaned_retail_sales.csv
│   ├── revenue_by_category.csv
│   ├── revenue_by_city.csv
│   └── monthly_revenue.csv

Documentation/
│
├── Project_Documentation.docx

PowerBI/
│
├── Retail_Sales_Dashboard.pbix

Screenshots/
│
├── dashboard.png
```

---

# Key Features

* Retail transaction data ingestion
* Duplicate handling
* Missing value treatment
* Product standardization
* PII masking
* Revenue KPI generation
* Interactive Power BI dashboard

---

# KPIs Implemented

* Total Revenue
* Total Orders
* Average Revenue
* Revenue by Category
* Revenue by City
* Monthly Revenue Trend
* Product-wise Revenue Analysis

---

# Dashboard Insights

* Electronics generated the highest revenue
* Chennai achieved the highest city-wise revenue
* Laptop products contributed the highest sales revenue

---

# Power BI Dashboard

The dashboard contains:

* KPI Cards
* Revenue Trend Analysis
* Product Performance
* Revenue by Category
* Revenue by City
* Interactive slicers

---

# Scalability

The local pipeline can be extended to cloud platforms such as:

* Azure Data Factory
* Azure Databricks
* Azure Data Lake
* SQL-based Data Warehouses
