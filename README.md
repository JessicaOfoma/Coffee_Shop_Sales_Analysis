# Coffee_Shop_Sales_Analysis
## Overview

This project analyzes sales transactions from a coffee shop using Microsoft Excel. The objective was to uncover trends in customer behavior, product performance, and time-based sales patterns, and to present those insights through a dynamic, easy to use dashboard.

## Key Steps

### Data Preparation

- Cleaned and structured the raw dataset for analysis.
- Applied Excel filters to **inspect values in each field**, ensuring consistency and catching potential errors.
- Checked for and removed any **duplicates** or **blank fields** that might affect analysis accuracy.
- Verified proper formatting for date and time columns to support time based breakdowns (e.g., by month, weekday, and hour).
- Created **new helper columns** such as:
  - Month names from transaction dates
  - Hour of day segments
  - Weekday names
### Pivot Table Analysis

#### Monthly Revenue Summary:
Created a pivot table showing **total revenue per month**, allowing for trend analysis and helping to identify peak revenue periods.

#### Day-of-Week Transaction Analysis:
Analyzed **count of transactions by day of the week** to understand customer foot traffic trends and identify the busiest weekdays.

#### Hour-of-Day Sales Activity:
Analyzed **transaction counts by the hour of day** (based on the raw transaction time column). This helped identify peak sales periods, with the highest activity observed during the morning rush hours.


#### Product Category Popularity:
Used a pivot table to show **count of transactions by product category** (e.g., Coffee, Tea, Bakery). This helped determine which categories are most frequently purchased.

#### Top 15 Selling Products:
Created a ranked list of the **top 15 products** based on the number of transactions. This identified the highest performing individual items across all locations.

### Dashboard Creation

Designed an interactive Excel dashboard incorporating:
- **PivotTables** and **PivotCharts** for data exploration
- **Slicers** to allow filtering by location
- **Conditional formatting** to highlight key figures and trends

The dashboard provides a clear, user friendly interface for analyzing sales data in real time.

## Insights & Outcomes

- Revenue trends show monthly variability, with identifiable peak seasons. The highest total revenue was recorded in **May and June**, indicating strong mid-year performance.
- **Thursdays and Fridays** had the highest number of transactions, indicating busy end-of-week activity.
- The majority of transactions occurred in the **morning hours (7 AM–10 AM)**, aligning with typical coffee consumption habits.
- **Coffee** dominated all product categories in terms of transaction volume, indicating it is the core driver of customer purchases and potentially a key revenue stream for the business. This suggests that coffee-related promotions, loyalty programs, or bundling strategies (e.g., coffee + pastry) could significantly enhance overall sales performance.
**Tip:** Use the slicers in the dashboard to explore how insights change across different locations, product types, or time ranges.

## Tools Used

- **Microsoft Excel**
  - Data Cleaning
  - Pivot Tables & Charts
  - Dashboard Design (Slicers, Conditional Formatting)

## Skills Demonstrated

- Data Cleaning & Preprocessing
- Time and Category-Based Sales Analysis
- Dashboard Design in Excel
- Data Visualization
- Business Insight Extraction
