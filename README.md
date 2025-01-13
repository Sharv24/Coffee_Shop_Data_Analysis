# Coffee_Shop_Data_Analysis
Project Overview

This project focuses on analyzing the sales data of a coffee shop using Power BI. The analysis provides actionable insights into sales trends, customer behavior, and product performance. By visualizing key performance indicators (KPIs) and creating interactive dashboards, this project aims to empower decision-making for improved business outcomes.

Problem Statement

The objective of this project is to address the following business requirements:

KPI's Requirements

Total Sales Analysis:

Calculate the total sales for each respective month.

Determine the month-on-month increase or decrease in sales.

Calculate the difference in sales between the selected month and the previous month.

Total Orders Analysis:

Calculate the total number of orders for each respective month.

Determine the month-on-month increase or decrease in the number of orders.

Calculate the difference in the number of orders between the selected month and the previous month.

Total Quantity Sold Analysis:

Calculate the total quantity sold for each respective month.

Determine the month-on-month increase or decrease in the total quantity sold.

Calculate the difference in the total quantity sold between the selected month and the previous month.

Charts Requirements

Daily Sales Analysis with Average Line:

Display daily sales for the selected month with a line chart.

Incorporate an average line on the chart to represent the average daily sales.

Highlight bars exceeding or falling below the average sales to identify exceptional sales days.

Sales Analysis by Product Category:

Analyze sales performance across different product categories.

Provide insights into which product categories contribute the most to overall sales.

Top 10 Products by Sales:

Identify and display the top 10 products based on sales volume.

Allow users to quickly visualize the best-performing products in terms of sales.

Sales Analysis by Days and Hours:

Utilize a heat map to visualize sales patterns by days and hours.

Implement tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day-hour.

Step-by-Step Project Actions

1. Data Cleaning in Excel

Objective: Prepare the raw dataset for analysis.

Steps:

Open the dataset in Excel.

Remove any duplicate rows to ensure data integrity.

Handle missing values by either filling them with appropriate values (e.g., 0 for sales or orders) or removing incomplete rows.

Standardize column headers (e.g., rename "Order Date" to "Date" and ensure consistent formatting).

Verify data types (e.g., ensure dates are in date format and numerical columns are formatted correctly).

Save the cleaned dataset as a CSV file.

2. Data Import and Preparation in Power BI

Objective: Load the cleaned data into Power BI for further processing.

Steps:

Open Power BI Desktop.

Import the cleaned CSV file into Power BI.

Check the data model and relationships between tables (if multiple tables are used).

Create calculated columns or measures as needed using DAX (e.g., Total Sales = SUM(Sales)).

3. KPI Analysis

Objective: Calculate and visualize key performance indicators.

Steps:

Create measures for Total Sales, Total Orders, and Total Quantity Sold.

Use line or bar charts to display month-on-month trends.

Add comparison visuals to show differences between selected months.

4. Visualizing Daily Sales with Average Line

Objective: Identify exceptional sales days.

Steps:

Create a line chart for daily sales.

Add an average line using a calculated measure (e.g., Average Sales = AVERAGE(Daily Sales)).

Highlight days exceeding or falling below the average using conditional formatting.

5. Analyzing Sales by Product Category

Objective: Understand category-wise performance.

Steps:

Use a bar chart to display sales by category.

Sort categories by total sales to identify top contributors.

6. Identifying Top 10 Products by Sales

Objective: Showcase best-performing products.

Steps:

Create a ranking measure using DAX (e.g., RANKX function for sales volume).

Display the top 10 products in a table or bar chart.

7. Sales Analysis by Days and Hours

Objective: Identify peak sales times.

Steps:

Create a heat map visualization using a matrix chart.

Configure rows as days and columns as hours.

Add tooltips to display detailed metrics (e.g., total sales, orders, quantity).

Features of the Dashboard

Interactive Visuals: Filter and drill down data by month, product category, and time.

Key Metrics Display: KPIs for total sales, total orders, and total quantity sold.

Dynamic Analysis: Month-on-month comparisons and trend identification.

Heatmap Visualization: Highlight peak sales hours and days for operational optimization.

Top Product Insights: Showcase best-performing products for targeted marketing strategies.

Tools and Technologies

Data Visualization: Power BI

Data Source: Coffee shop sales dataset

Techniques: Data cleaning, aggregation, DAX calculations, and interactive dashboard design

How to Use

Clone the repository to your local machine.

Open the Power BI file (.pbix) to explore the dashboard.

Use the interactive filters to analyze specific months, categories, or time periods.

Insights and Outcomes

Identified seasonal trends in coffee shop sales.

Highlighted the best-performing product categories and top 10 products.

Pinpointed peak sales times for better resource allocation.

Enabled data-driven decision-making through actionable insights.

Future Scope

Integrate real-time data for live updates.

Expand analysis to include customer demographics and preferences.

Incorporate predictive analytics for forecasting future sales trends.
