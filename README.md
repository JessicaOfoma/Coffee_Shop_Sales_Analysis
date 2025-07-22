# Coffee Shop Sales Analysis
![Dashboard Screenshot](https://github.com/JessicaOfoma/Coffee_Shop_Sales_Analysis/blob/main/dashboard.JPG?raw=true)
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

- Revenue trends show monthly variability, with identifiable peak seasons particularly in **May and June**, which recorded the highest total revenue presenting an opportunity to launch seasonal promotions, product bundles, or loyalty incentives to boost sales and customer retention during this high-demand period.
- **Thursdays and Fridays** recorded the highest number of transactions, indicating busy end-of-week activity. This presents an ideal window to introduce end-of-week specials, happy hour discounts, or targeted marketing campaigns aimed at increasing average transaction value during these high-traffic days.
- The majority of transactions occurred in the **morning hours (7AM – 10AM)**, aligning with typical coffee consumption habits. This highlights the need to optimize morning operations by ensuring full staff availability, quick service, and product readiness. Additionally, implementing morning-exclusive promotions such as breakfast combos or time-sensitive discounts can help drive even more sales.
- **Coffee** dominated all product categories in terms of transaction volume, indicating it is the core driver of customer purchases and potentially a key revenue stream for the business. To leverage this, consider introducing coffee-centric loyalty programs, cross-selling with complementary items such as pastries, and testing premium options like specialty brews or seasonal flavors to boost transaction value and strengthen brand differentiation.

**Tip:** Use the slicers in the dashboard to explore how insights change across different locations.

## Tools Used

- **Microsoft Excel**
  - Data Cleaning
  - Pivot Tables & Charts
  - Dashboard Design (Slicers, Conditional Formatting)

## Skills Demonstrated

- Data Cleaning & Preprocessing
- Time and Category-Based Sales Analysis
- Dashboard Design in Excel
- Exploratory Data Analysis
- Data Visualization
- Business Insight Extraction
