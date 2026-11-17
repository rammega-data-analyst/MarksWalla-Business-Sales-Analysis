# MarksWalla – Business & Sales Analysis Dashboard

## Project Overview

The **MarksWalla – Business & Sales Analysis Dashboard** is an Excel-based data analytics project focused on analysing business sales performance for the year 2025.

The objective of this project is to clean and transform raw sales data, analyse business performance, identify key trends, calculate important business KPIs, and develop an interactive dashboard to support data-driven business decisions.

## Project Objectives

- Analyse overall sales and business performance.
- Identify and remove duplicate records.
- Handle missing values and data inconsistencies.
- Perform data validation and data type verification.
- Calculate important sales and profitability metrics.
- Analyse sales performance by region, category, product, and month.
- Develop interactive visualisations using Excel PivotTables, PivotCharts, and Slicers.
- Provide actionable business insights and recommendations.

## Dataset Description

The dataset contains sales transaction information for the year 2025.

| Dataset Details | Information |
|---|---|
| Original Records | 1,000 |
| Original Columns | 14 |
| Duplicate Records Removed | 20 |
| Final Unique Records | 980 |
| Missing Cells Initially Identified | 71 |
| Missing Cells Handled After Duplicate Removal | 70 |
| Remaining Blank Cells | 0 |
| Unknown Values | 18 |
| Analysis Period | January–December 2025 |

### Dataset Columns

Order ID, Order Date, Customer ID, Customer Name, Region, City, Product Name, Category, Quantity, Unit Selling Price, Unit Cost, Discount, Stock Available, and Order Status.

## Data Cleaning & Preparation

The raw dataset was inspected and cleaned using Microsoft Excel.

### 1. Duplicate Removal
- Identified 20 exact duplicate records.
- Used Excel's Remove Duplicates feature.
- Retained 980 unique records.

### 2. Missing Value Handling
- Identified 71 missing cells in the original dataset.
- Handled 70 remaining missing cells after duplicate removal.
- Used "Unknown" for uncertain City and Order Status values.
- Verified that no blank cells remained in the cleaned dataset.

### 3. Data Consistency
- Checked Region, City, Category, and Order Status values.
- Corrected the inconsistent category spelling "Electronics." to "Electronics".
- Verified numerical fields for invalid values.

### 4. Data Type Verification
- Verified all 14 original columns.
- Checked date, text, and numerical data types.
- Completed data consistency checks.

## Data Transformation

Created additional calculated columns to support business analysis:

| Calculated Column | Formula |
|---|---|
| Gross Sales | Quantity × Unit Selling Price |
| Discount Amount | Gross Sales × Discount Percentage |
| Net Sales | Gross Sales − Discount Amount |
| Total Cost | Quantity × Unit Cost |
| Gross Profit | Net Sales − Total Cost |
| Profit Margin | Gross Profit ÷ Net Sales |

Additional date columns:
- Month
- Year
- Month-Year

## Excel Techniques & Functions Used

- Data Cleaning
- Duplicate Removal
- Missing Value Handling
- Data Type Verification
- Data Validation
- Data Transformation
- Calculated Columns
- Excel Formulas: IFERROR, SUMIFS, COUNTIF, TEXT, YEAR, MEDIAN, FILTER
- PivotTables
- PivotCharts
- Interactive Slicers
- Report Connections
- Currency and Percentage Formatting
- Interactive Dashboard Development

## Sales Analysis Modules

### 1. Region-wise Sales Analysis
Analysed sales performance across East, West, North, and South regions to identify the highest sales-contributing region.

### 2. Category-wise Sales Analysis
Compared sales performance across Electronics, Furniture, Accessories, Lifestyle, and Stationery categories.

### 3. Product-wise Sales Analysis
Evaluated individual product contributions and identified top-performing products.

### 4. Monthly Sales Trend Analysis
Analysed monthly sales performance from January to December 2025 to identify fluctuations and stronger sales periods.

## Key Performance Indicators (KPIs)

The overall dashboard KPI snapshot, before applying slicer filters:

| KPI | Result |
|---|---:|
| Total Quantity Sold | 4,437 |
| Total Orders | 980 |
| Total Net Sales | ₹4,05,92,218.50 |
| Total Gross Profit | ₹71,34,368.50 |
| Profit Margin | 17.58% |
| Average Order Value | ₹41,420.63 |

## Interactive Dashboard

Developed an interactive Excel dashboard using a green and white theme.

### Dashboard Components

**Six KPI Cards**
- Total Quantity Sold
- Total Orders
- Net Sales
- Gross Profit
- Profit Margin
- Average Order Value

**Four PivotCharts**
- Region-wise Sales – Column Chart
- Category-wise Sales – Bar Chart
- Product-wise Sales – Bar Chart
- Monthly Sales Trend – Line Chart

**Four Interactive Slicers**
- Year
- Region
- Category
- Order Status

Connected the Slicers to the Sales PivotTables and KPI PivotTable using Report Connections. This enables dynamic filtering of charts and KPI values based on user selections.

## Interactive Dashboard

![MarksWalla – Business & Sales Analysis Dashboard](Dashboard%20Screenshot.png)


## Key Business Insights

1. **Regional Performance:** East recorded the highest sales contribution among the regions.
2. **Category Performance:** Electronics was the leading category, followed by Furniture.
3. **Product Performance:** Laptop recorded the highest sales contribution.
4. **Monthly Performance:** July appeared as a strong sales period, while sales fluctuated across the year.
5. **Profitability:** The overall Gross Profit Margin was 17.58%.

## Business Recommendations

- Study the successful sales performance of the East region and identify opportunities to improve other regions.
- Monitor inventory levels for high-performing products such as Laptops.
- Review lower-contributing product categories and explore opportunities to improve their sales.
- Analyse monthly sales fluctuations and plan suitable promotional activities.
- Monitor Net Sales, Gross Profit, and Profit Margin regularly to support profitable business growth.

## Project Outcome

Successfully transformed raw sales data into a structured and interactive business analysis solution.

The project demonstrates the complete data analytics workflow, including data cleaning, data transformation, KPI calculation, sales analysis, data visualisation, dashboard development, and business recommendations.

## Conclusion

This project demonstrates how Microsoft Excel can be used to convert raw business data into meaningful insights.

By removing duplicate records, handling missing values, validating data, creating calculated columns, developing PivotTables and PivotCharts, and implementing interactive Slicers, I developed a dynamic dashboard to monitor business performance.

The final analysis helps management understand sales contributions, identify top-performing regions and products, monitor profitability, and make informed business decisions.

## Tools & Technologies

**Microsoft Excel | PivotTables | PivotCharts | Slicers | Excel Formulas | Data Cleaning | Data Analysis | Dashboard Development**
