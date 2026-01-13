📌 Project Overview
This project demonstrates an end-to-end data analysis workflow, from building a database to creating an interactive business intelligence dashboard. The goal was to analyze sales performance, profit margins, and growth trends for a high-end audio technology company.

🛠 Tools & Technologies
Database: Microsoft SQL Server

Data Visualization: Power BI

Language: SQL (T-SQL)

Concepts: Data Modeling, ETL, DAX (Data Analysis Expressions), Data Cleaning.

🚀 Implementation Steps
1. Database & Data Cleaning (SQL Server)
Created a local SQL database and imported raw datasets (Sales, Products, and Discounts).

Performed data cleaning and transformation using SQL Queries.

Utilized CTEs (Common Table Expressions) and JOINs to aggregate data and calculate essential business metrics before importing to Power BI.

2. Data Integration & Transformation
Connected Power BI to the SQL Server database to ensure data integrity and real-time updates. 
+1

Further refined the data in Power Query to ensure all data types were correct for visualization.

3. Data Modeling & DAX
Established a star schema data model for efficient filtering.

Developed custom DAX measures to calculate:

Total Revenue & Total Profit

Year-over-Year (YoY) Growth

Unit Sales Trends

Profit Margins by Product Category

4. Dashboard Design
Built an interactive one-page dashboard featuring:


Image Slicers: Allows users to filter the entire report by selecting specific product images. 
+1


Custom Tooltips: Hover effects that reveal deeper insights into customer segments and pricing strategies. 

Geospatial Analysis: Revenue breakdown by country to identify top-performing markets.

Time-Series Analysis: Visualizing sales peaks and valleys across different months and years.

📈 Key Insights
Identified high-performing product categories that drive the majority of the profit.

Discovered specific discount bands that maximize volume without significantly eroding margins.

Analyzed seasonal trends to help stakeholders plan for inventory and marketing campaigns.

📂 Repository Contents

sales.pbix: The complete Power BI project file including the data model and dashboard. 
+1

SQL_Queries.sql: (Optional - Add your SQL script file here) The scripts used for database setup and data transformation.

🔗 Credits
This project was inspired by and implemented following the tutorial by Absent Data.
