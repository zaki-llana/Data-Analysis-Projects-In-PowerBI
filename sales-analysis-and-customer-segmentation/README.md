# Sales Analysis and Customer Segmentation on Walmart's Operational and Sales Dataset

## Project Overview
Comprehensive Power BI dashboard analyzing Walmart sales performance and customer demographics across 5K transactions with $15.26M sales

## Key Insights
- **Promotional Impact:** Promotions increase sales by 11%
- **Peak Month:** August with $2.02M in sales
- **Critical Alert:** 55% sales drop in September ($0.91M)
- **Top Product:** Tablets led with $9.23M sales
- **Customer Breakdown:** 2.88K one-time customers, 0.97k repeat customers
- **Top City:** Los Angeles ($3.28M sales)

## Dashboards
- **Overview** - Sales trends by month, city, product, and category
- **Sales Analysis** - Weekday patterns, payment methods, loyalty levels, and promotions
- **Customer Segmentation** - Customer growth, income brackets, and demographics

## Workflow & Process
1. **Data Acquisition**
- Downloaded dataset from Kaggle
- Stored locally for processing

2. **Data Preprocessing**
- Fixed data type inconsistencies
- Standardized formatting (dates, text, and numeric)
- Created derived columns
- Restructured for analysis

3. **Data Modeling**
- Designed star schema data model (single fact table and multiple dimension tables)
- Established relationships between tables

4. **Calendar Table**
- Added year, quarter, month, week attributes
- Enabled time-based analysis and comparisons

5. **Feature Engineering**
- Built DAX measures for KPIs:
  - Total Sales, Total Products Sold, Transaction Count
  - Average Order Value, Sales With Promo, Top Store, Top Product
  - One-Time Customers, Repeat Customers, Repeat Rate

6. **Visualization**
- Built 3 main report pages (Overview, Sales Analysis, Customer Segmentation)
- Designed interactive visuals 
- Added filters 

## Tools Used
- **Power Query:** Data cleaning & transformation
- **Power BI:** Data modeling & visualization
- **DAX:** Measures & calculations

## Files
- `sales-customer-analysis.pbix` - Main Power BI file
