# powerbi-retail-grocery-sales
Interactive Power BI dashboard analyzing retail grocery sales

https://app.powerbi.com/view?r=eyJrIjoiZjk4YWQ3NGItMjJkYy00NWI4LWIyNDUtN2MyMWRjMDI3MjMxIiwidCI6IjcwZGUxOTkyLTA3YzYtNDgwZi1hMzE4LWExYWZjYmEwMzk4MyIsImMiOjN9

📊 Retail Grocery Sales Dashboard – Power BI
🔍 Project Overview
This project focuses on analyzing retail grocery sales data using Power BI to provide actionable insights into sales performance, customer purchasing behavior, and geographic demand.
The dashboard is designed for business users and decision-makers, offering a clean and interactive experience.
🧱 Data Model
Implemented a star schema
Created a dedicated Date Table
Connected fact and dimension tables using one-to-many relationships
Enabled proper time intelligence
Fact Table:
Sales (Quantity, Sales Amount, Transactions)
Dimension Tables:
Products
Categories
Customers
Cities
Countries
Date
📌 Key KPIs (Built as Measures)
Total Sales
Sales Month-over-Month %
Total Quantity Sold
Total Transactions
Average Order Value (AOV)
All KPIs are implemented as DAX measures for flexibility, performance, and accuracy.
📈 Visualizations Included
KPI Cards (Executive summary)
Total Sales by Category
Total Sales by Product
Monthly Sales Trend
Products Sold by Category (Donut Chart)
Products Sold by City (Map)
Products Sold vs Sales by Category (Scatter Plot)
🔄 Interactivity Features
Cross-filtering between visuals
Tooltips for detailed insights
Date-based trend analysis
Geographic filtering using maps
⚠️ Challenges Faced & Solutions
Challenge	Solution
Month sorting incorrect	Created MonthNumber in Date table
Date hierarchy confusion	Used Date table instead of auto hierarchy
KPIs created as columns	Rebuilt as DAX measures
Cluttered visuals	Applied consistent theme and layout
Oversized map bubbles	Adjusted bubble size in formatting
🎯 Business Insights
Confections and Meat are top revenue contributors
Sales peak during early months and decline toward May
High-volume cities drive both sales and transaction count
Some categories sell high volume but generate lower revenue (pricing insight)
🛠️ Tools & Technologies
Power BI Desktop
DAX
Data Modeling
Time Intelligence
Data Visualization Best Practices
🚀 Future Improvements
Year-over-Year (YoY) analysis
Profit & margin KPIs
Category contribution %
Drill-through detail pages
Forecasting visuals

Upendar Reddy
Aspiring Data Analyst / BI Analyst
📫 Open to analytics opportunities
