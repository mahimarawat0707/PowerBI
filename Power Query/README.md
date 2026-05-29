# Sales Analytics Dashboard – Power BI Project

## Project Overview
This Power BI dashboard provides a complete sales analysis solution using interactive visualizations and advanced Power Query transformations. The dashboard helps analyze sales performance, freight costs, tax amounts, customer segmentation, product color preferences, and geographical sales distribution.

The project focuses on:
- Business Intelligence
- Data Cleaning & Transformation
- KPI Monitoring
- Trend Analysis
- Interactive Dashboard Design

---

# Tools & Technologies Used

- **Power BI Desktop**
- **Power Query Editor**
- **DAX (Data Analysis Expressions)**
- **Data Modeling**
- CSV/Excel Dataset

---

# Dashboard Features

## KPI Cards
The dashboard contains major business KPIs:
- **Total Sales Amount:** 179.41M
- **Total Freight:** 4.49M
- **Total Order Quantity:** 565K
- **Total Tax Amount:** 14.35M

These KPIs provide quick insights into overall business performance.

---

## Sales Trend Analysis
### Visualization:
- Bar Chart (Sales Amount by Year & Month)

### Insights:
- Monthly sales performance tracking
- Year-wise comparison
- Seasonal trends identification
- Business growth monitoring

---

## Geographical Sales Analysis
### Visualization:
- Map Chart

### Insights:
- Country-wise sales distribution
- Regional performance analysis
- Global sales presence visualization

---

## Decomposition Tree Analysis
### Visualization:
- Decomposition Tree

### Drilldown Used:
- Gender
- Product Color

### Insights:
- Customer segmentation
- Product preference analysis
- Sales contribution breakdown

---

# Power Query Transformations Used

The project heavily uses **Power Query** for data preprocessing and cleaning.

## Data Cleaning
- Removed null values
- Removed duplicates
- Renamed columns
- Changed data types

## Data Transformation
- Split columns
- Merged columns
- Extracted date fields
- Conditional columns
- Replaced values

## Data Shaping
- Filtered unnecessary records
- Sorted data
- Grouped rows
- Pivot/Unpivot operations

## Query Optimization
- Created reusable queries
- Applied step-by-step transformations
- Improved data consistency

---

# DAX Measures Used

Some important measures created using DAX:
```DAX
Total Sales = SUM(Sales[Sales Amount])

Total Freight = SUM(Sales[Freight])

Total Quantity = SUM(Sales[Order Quantity])

Total Tax = SUM(Sales[Tax Amount])