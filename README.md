 Smart Retail Lakehouse Pipeline (Medallion Architecture)

A Databricks-based Medallion Architecture project using SQL, PySpark, and Python to process retail transaction data across Bronze, Silver, and Gold layers.

## 🥉 Bronze Layer
- Ingest raw orders, customers, products, and payments
- Store data in original format for traceability

## 🥈 Silver Layer
- Clean and standardize data using PySpark & SQL
- Remove duplicates and fix data types
- Apply validation rules

## 🥇 Gold Layer
- Build analytics-ready tables
- Calculate KPIs:
  - Total revenue
  - Top products
  - Customer performance
  - Sales by country

## ⚙️ Tech Stack
- Databricks
- SQL
- PySpark
- Python

## Architecture
Medallion (Bronze → Silver → Gold)

## Output
Business-ready datasets for dashboards and reporting

