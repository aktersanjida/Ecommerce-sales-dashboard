# E-Commerce Sales Dashboard

## Project Overview

This project aims to create a Sales Dashboard for a US-based E-commerce Sales Company, focusing on various KPIs and insights to inform future business strategies.

## Problem Statement

The company requires a Sales Dashboard displaying Year-to-Date (YTD) sales information and insights, including:

- **KPI Banner:** Showing YTD Sales, YTD Profit, YTD Quantity Sold, and YTD Profit Margin.
- **Year-on-Year Growth:** Calculating YoY growth for each KPI with monthly trend sparklines.
- **Customer Category Analysis:** YTD Sales, PYTD Sales, and YoY Sales growth with trend icons for each category.
- **State-wise Sales Performance:** Analyzing YTD Sales across different states.
- **Product Performance:** Highlighting the top 5 and bottom 5 products by sales.
- **Regional Sales:** Identifying best and worst performing regions.
- **Shipping Type Analysis:** Determining the best-performing shipping type by percentage.

## Steps Taken

### Data Importation

- The dataset was sourced from Kaggle.
- Data was imported into MS SQL Server.
- Connected Power BI to MS SQL Server for data fetching.

### Data Preprocessing

- Performed data cleaning and modeling using Power Query.
- Created a 'Calendar' table to extract months from the original table.
- Utilized DAX functions (Calculate, Sum, Sumx, Filter, values, selectedvalue, return, concatenate, divide, var, etc.) and Time Intelligence functions (TOTALYTD, SAMPERIODLASTYEAR, etc.) to create calculated measures.

### Data Visualization

- Created an insightful dashboard using various visualization methods: Area charts, Bar charts, Donut chart, Slicer, Matrix, and Map.

## Insights

### YTD Sales Analysis

- **Overall YTD Sales:** $3,496,845
- Customer segments such as "Mary" show significantly higher sales.
- YTD Sales have decreased by 0.83% compared to the previous year.

### YTD Profit Analysis

- **Overall YTD Profit:** $388,948.30
- Certain customer segments show notably higher profits.

### YoY Profit Analysis

- **Overall YoY Profit:** -2.95%
- States like WV show significantly higher profits.

### YTD Quantity Analysis

- **Overall YTD Quantity:** 32,887
- Customer segments such as "Mary" show higher quantities sold.

### YoY Quantity Analysis

- **Overall YoY Quantity:** -6.55%
- States like ND show higher quantities sold.

### YTD Profit Margin Analysis

- **Overall YTD Profit Margin:** 11%
- Some segments significantly outperform others.

## Visualizations

The dashboard uses the following visualization methods:
- Area charts
- Bar charts
- Donut chart
- Slicer
- Matrix
- Map

## Conclusion

This E-Commerce Sales Dashboard provides valuable insights into sales performance across different regions, customer segments, and product categories. The analysis helps in understanding trends and making data-driven decisions for future business strategies.

## Technologies Used

- Power BI
- MS SQL Server
- Power Query
- DAX


**Keywords:** Data Analytics, E-commerce, Sales Dashboard, Data Visualization, Business Intelligence, Power BI, SQL, DAX, KPI
