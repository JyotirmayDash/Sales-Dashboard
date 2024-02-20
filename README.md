# Power BI AdventureWorksLT Sales Report
#### Overview
This repository contains a Power BI report developed as part of a Module 5 assignment. The report is built using Power BI Desktop and connects to the AdventureWorksLT database. The report showcases data shaping, combining, and various visualizations to analyze sales-related information.

# Instructions
##### Connecting to Data
Open Power BI Desktop.
Connect to the AdventureWorksLT database using the provided queries in Labexercise1.SQL.
Save the file as "AdventureWorksLT sales 5."
Shaping the Data
Customers Query:
##### Rename Query 1 to Customers.
Delete NameStyle and SalesPerson columns.
Hide the CustomerID column.
Change data categories as specified.
Add a new column, FullAddress.
Save the file.
Sales Query:
##### Rename Query 2 to Sales.
Delete RevisionNumber and SalesOrderNumber columns.
Hide specified columns.
Add a new column, LineTotal.
Create a measure, TargetSales.
Save the file.
##### Combine the Data
Create a new table, Sales by States, by importing the States table.
Import the list of states from Wikipedia.
Perform data cleaning steps.
Merge data with Sales by States using State Code Long.
Set privacy levels and save the file.
##### Add Visualizations
Gauge chart for LineTotal and TargetSales.
Pie chart for Top Selling Companies.
Stacked bar chart for Sales by Main Category with a constant line.
Donut chart for Sales by Main Category.
Stacked column chart for Top Selling Bikes with filters and a constant line.
Save the report and add a new page.
##### Additional Visualizations
Map visual for World Sales by City.
Map visual for Sales by State.
Save the report.
##### Usage
Download and open the Power BI file.
Interact with different pages and visuals.
Explore the data insights presented in the report.
##### Credits
Developed by Jyotirmay Dash
