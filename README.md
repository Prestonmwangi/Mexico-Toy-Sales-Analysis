# Maven Toys Sales Analysis - Power BI Dashboard

## Project Overview
This project is a Power BI dashboard analyzing **sales, revenue, profitability, products, and store performance** for Maven Toys, a fictional toy retailer operating across Mexico.

The dashboard is designed to help stakeholders quickly understand overall business performance and identify high-performing products, stores, and locations.

## Dashboard Pages & Features

### 1. Executive Sales & Profit
The executive page gives an overview of the company's overall performance.
Key Performance Indicators (KPIs): Total Orders (829K), Total Units (1M), Total Revenue ($14.44M), Total Profit ($4.01M), and Profit Margin (27.79%).

Performance Trends: A monthly chart comparing Total Revenue and Total Profit across 2022–2023.

Product Performance: Bar charts showing Total Revenue and Profit Margin % by Product Category.

City Performance: Bar chart highlighting the Top 5 Cities by Total Profit.

*Insight*: Toys generate the highest revenue, while Electronics achieve the highest profit margin.

![Executive Sales & Profit](https://github.com/Prestonmwangi/Mexico-Toy-Sales-Analysis/blob/main/Images/Executive%20Sales%20%26%20Profit.png)
*Caption: Executive overview of sales, profitability, category performance, and city-level results.*

### 2. Store & Product Performance

The second page focuses on store and product performance.

Key Performance Indicators (KPIs): Total Stores (50), Total Products (35), Average Revenue/Store ($288.89K), Average Profit/Store ($80.28K), and Profit Margin (27.79%).

Store Performance: Scatter and table visuals comparing Total Revenue, Total Profit, and Total Units by store.

Product Performance: Bar charts showing the Top 5 Products by Orders and Total Profit.

Location Performance: Column chart comparing Revenue and Profit across store locations.

*Insight*: Downtown stores generate the highest revenue and profit, while Colorbuds leads product sales volume and profit.

![Store & Product Performance](https://github.com/Prestonmwangi/Mexico-Toy-Sales-Analysis/blob/main/Images/Store%20%26%20Product%20Performance.png)
Caption: Store and product performance showing top products, individual store results, and revenue and profit by store location.

## Interactive Elements
The report features a custom-built, unified navigation pane on the left side of every page:
**page navigation buttons** : Allows users to seamlessly toggle between the "Executive Sales & Profit" and "Store & Product Performance" pages.
**slicers** for:
    * Year & Month (2022 & 2023)
    * Product Category
    * Store City
    * Store Location

## Data Model & DAX

The report uses related **Sales, Products, and Stores** tables to support the analysis.
DAX measures were created for core business metrics including **Total Orders, Total Units, Total Revenue, Total Cost, Total Profit, Profit Margin, and store-level averages**.
Revenue and profit are calculated using sales units together with product price and cost information.

## How to Use

1. Download the `.pbix` file.
2. Open it in **Power BI Desktop**.
3. Use the page buttons to navigate between dashboards.
4. Use the slicers to explore different periods, products, cities, and store locations.
