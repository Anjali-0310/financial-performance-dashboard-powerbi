
# Financial Performance Dashboard — Power BI

## Overview

An interactive Power BI dashboard developed to analyze financial performance across products, countries, customer segments, and time.

The dashboard transforms financial sales data into an interactive business reporting view that helps identify sales trends, product performance, country-level performance, and segment profitability.

## Dashboard Preview

<img width="680" height="539" alt="Screenshot 2026-09-06 154147" src="https://github.com/user-attachments/assets/b59c9076-ed27-4555-a0ae-3f1544222540" />

## Objectives

- Analyze overall financial performance
- Track sales trends over time
- Compare sales across countries
- Analyze product-level sales performance
- Compare profitability across customer segments
- Enable interactive analysis using dashboard filters

## Key Features

### KPI Analysis
- Total Sales
- Total Units Sold
- Total Profit
- Profit Margin

### Business Analysis
- Sales trend by year
- Sales by country
- Sales by product
- Profit by customer segment
- Segment-level performance comparison

### Interactive Filters
The dashboard includes slicers for:

- Year
- Country
- Segment
- Product

These filters allow users to dynamically explore different parts of the dataset.

## Tools & Technologies

- Power BI Desktop
- DAX
- Microsoft Excel
- Data Visualization
- Business Analytics

## Dataset

The project uses the Financial Sample dataset containing financial and sales-related information such as:

- Segment
- Country
- Product
- Units Sold
- Sales
- COGS
- Profit
- Date
- Year

## DAX Measures

The dashboard uses DAX measures for key business metrics.

### Total Sales

```DAX
Total Sales = SUM('Financials'[Sales])
