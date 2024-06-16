# E-Commerce Sales Dashboard

I am thrilled to share a data analysis project named **E-Commerce Sales Dashboard** which I completed using **Power BI**. This project aims to find the necessary KPIs and analyze the sales for different regions and segments, which will help determine future valuable strategies for the business.

## Problem Statement:

A US Based E-commerce Sales Company wants us to create a Sales Dashboard showing information of YTD sales and generate insights for the following:

- Create a KPI Banner showing YTD Sales, YTD Profit, YTD Quantity sold, YTD Profit Margin.
- Find Year-on-year growth for each KPI and show a YTD sparkling for each measure in the KPI to understand the monthly trend for each fact.
- Find YTD Sales, PYTD Sales, and YoY Sales growth for different customer categories. Add a trend icon for each category.
- Find YTD Sales performance by each State.
- Top 5 and Bottom 5 Products by Sales.
- YTD Sales by Region to know the best and worst performing regions all over the country.
- YTD Sales by shipping type to get the best shipping type percentage.

## Steps:

1. **Import data in MS SQL Server**

   The origin of the dataset is from Kaggle. Then the data is imported into the MS SQL Server. Power BI is connected to MS SQL Server to fetch the data.

2. **Data Preprocessing**

   After importing the data from the data source, performed data cleaning and data modeling using Power Query. A new table named 'Calendar' was generated to extract months from the original table. DAX functions like `Calculate`, `Sum`, `Sumx`, `Filter`, `values`, `selectedvalue`, `return`, `concatenate`, `divide`, `var`, etc. were used to append or create calculated measures. Time Intelligence functions (`TOTALYTD`, `SAMPERIODLASTYEAR`, etc.) were also used.

3. **Data Visualization**

   This insightful dashboard shows an overview of multiple parameters and KPIs. Different types of visualization methods like Area charts, Bar charts, Donut chart, Slicer, Matrix, and Map are used.

## Insights

- The YTD sales have decreased by 0.83% compared to the previous year as well as the quantity, which decreased by 7.29%.
- YTD sales have increased by 2.61% for the Central region's people who are basically from Texas.
- Most revenue has come from the West region, and the YTD Sales are $4M. In this region, the YoY sales for office supplies have decreased but the sales for furniture have increased. The standard class shipping type is almost 60%.
- The South region has given the most amount of losses. YTD sales and profit have decreased simultaneously in this region.
- The top product is Staple envelope. Also, the most sold category is office supplies.
- The sales from the standard class shipping type is almost 60%.

## Hashtags

#PowerBI #MSSQL #Analysis #DAX #PowerQuery #DataModeling #DataScience #DataAnalyst #DataEngineer #DataVisualizationCommunity #BusinessIntelligenceCommunity #MarketingAnalytics #SalesDashboard #DataProject #DataDashboard #DataInsights #DataReporting #InteractiveDashboard #DataStorytelling
