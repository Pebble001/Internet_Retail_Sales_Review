# Internet Retail Sales Review (2009–2011)

A SQL and Power BI analysis of e-commerce sales data spanning 2009 to 2011. The project uncovers customer behaviour patterns, product performance, and geographic trends — with RFM-based customer segmentation.

---

## Overview

This project analyses an online retail business to answer key questions about revenue, customer loyalty, and sales seasonality. Data was loaded into Azure Data Studio, transformed using SQL, and visualised in Power BI.

**Business Questions:**
- Which countries and time periods drive the most sales?
- How are customers segmented by purchasing behaviour?
- What products are ordered most frequently?
- What seasonal patterns exist in sales?

---

## Tools Used
- **SQL** (Azure Data Studio) — unions, temp tables, RFM scoring
- **Power BI** — dashboard and interactive visualisations
- **Excel** — source data and export staging

---

## Methodology

1. Loaded multi-year data from Excel files into Azure Data Studio
2. Built UNION queries to combine tables across years
3. Created temporary tables (`#combinedtable`, `#RFM2`) for segmentation logic
4. Calculated RFM (Recency, Frequency, Monetary) scores per customer
5. Exported results to Excel and imported into Power BI
6. Built dashboard with quarter/year slicers for time-based filtering

---

## Key Findings

**Geography**
- United Kingdom leads in total orders across all periods

**Customer Segmentation**
- 77.32% of customers classified as high-value

**Seasonality**
- Q4 consistently records the highest sales each year
- November is the peak month for orders across all years

**Top Product**
- "White Hanging Heart T-Light Holder" — most ordered item

**Customer Behaviour**
- 67.71% of customers have low purchase frequency — re-engagement opportunity

---

## Dashboard Preview
> Add a screenshot of your Power BI dashboard here.

---

## SQL Queries
See the [`Internet-Retail-Queries`](./Internet-Retail-Queries) folder for all SQL scripts.

---

## How to Reproduce
1. Load the source Excel files into Azure Data Studio or SQL Server
2. Run the SQL scripts in the `Internet-Retail-Queries` folder
3. Export query results to Excel
4. Import into Power BI and connect visuals

---

## Data Source
Online retail transactional dataset (2009–2011) — publicly available on UCI Machine Learning Repository
