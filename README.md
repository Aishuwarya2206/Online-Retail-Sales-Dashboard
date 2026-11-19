# Online Retail Sales, Customer & Forecasting Dashboard

Interactive Power BI dashboard for online retail sales, customer segmentation, product profit and forecasting.

## Tools
Microsoft Power BI, Python, Excel

## Technologies
Power Query, DAX, Data Modeling, RFM Customer Segmentation, Market Basket Analysis, Sales Forecasting, Drillthrough, Custom Tooltips, Bookmarks, Slicers, Interactive Dashboard Design, Data Visualization

## Problem / Objective
Online retail transaction data across multiple countries, products, and customers is large and hard to analyze manually. It is difficult to track revenue trends, spot high-value and at-risk customers, find top-performing products, and plan future sales. The objective was to build an interactive Power BI dashboard that gives clear insights into sales performance, customer behavior, product profitability, cross-selling opportunities, and revenue forecasts.

## Action
- Cleaned and transformed the online retail dataset in Power Query.
- Built a data model with Date, Customer Summary, Recommendations, and Forecast tables.
- Created DAX measures: Total Revenue, Total Orders, Avg Order Value, Revenue Growth %, Gross Profit, Gross Profit Margin, Repeat Customer %, Top 20% Revenue Share.
- Segmented customers using RFM analysis (Champions, At-Risk).
- Applied market basket analysis (confidence and lift) for product recommendations.
- Added a 6-month revenue forecast with backtest MAPE.
- Designed a 7-page interactive dashboard with slicers, reset-filter buttons, drillthrough pages, tooltips, and bookmarks.

## Project Files
- `Online Retail_Dashboard.pbix` - Power BI dashboard
- `forecast_v2.csv` - sales forecast data
- `recommendations.csv` - market basket analysis rules (confidence, lift)

## Dashboard Screenshots

### Executive Overview
![Executive Overview](Executive%20Overview.png)

### Customer Analytics
![Customer Analytics](Customer%20Analysis.png)

### Product & Profit
![Product and Profit](Product%20and%20Profit%20.png)

### Forecasting & BI
![Forecasting and BI](Forcasting%20and%20BI.png)

### Product Details (Drillthrough)
![Product Details](Product%20Details.png)

### Customer Details (Drillthrough)
![Customer Details](Customer%20Details.png)

### Product Tooltip
![Product Tooltip](Product%20Tooltip.png)

## Result / Outcome
Reduced manual reporting effort, improved analysis and report generation speed, and increased sales and customer visibility through an interactive Power BI dashboard. It enables faster identification of revenue trends, top products, high-value and at-risk customers, cross-selling opportunities, and future sales demand.
