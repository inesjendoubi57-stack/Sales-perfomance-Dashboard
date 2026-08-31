# Sales-perfomance-Dashboard
Project Overview :
This project is an interactive Sales Performance Dashboard built using Power BI. It was created as
my first hands-on Power BI project to apply and strengthen my knowledge of data visualization, data
transformation, DAX, and data modeling.
The dashboard analyzes sales and customer data, providing insights into sales performance over time,
top-performing products, product categories, and customer-related information.
Project Objective :
The main objective of this project was to gain practical experience with Power BI by transforming raw
data into an interactive dashboard and exploring key sales performance metrics.
• Total Sales
• Total Number of Orders
• Total Number of Customers
• Sales Trends Over Time
• Top-Performing Products
• Sales Performance by Product Category
Dataset :
The dataset used in this project was obtained from the Data with Baraa YouTube channel for learning
and practice purposes.
The dataset consists of two files:
Customers Data
Contains customer-related information, including:
• Customer ID
• First Name
• Last Name
• Country
• State
• City
• Score
Orders Data
Contains sales and order-related information, including:
• Order ID
• Order Date
• Customer ID
• Product Name
• Product Category
• Quantity
• Sales
Data Preparation & Transformation :
Power Query
A Customer Name column was created by combining the First Name and Last Name fields into a
single column.
DAX
A calculated column called Clean Score was created using the COALESCE() function to replace
missing score values with 0.
Clean Score = COALESCE(customers_1000[score], 0)
Data Model :
The data model consists of two tables:
Customers — Contains customer-related information.
Orders — Contains order and sales information.
A one-to-many (1:*) relationship was created between the customers_1000 and orders tables using
customer-id as the key.
• One customer can have multiple orders.
• The cross-filter direction is set to Single.
This relationship enables customer information to be connected with order and sales data for analysis.
Business Questions :
1. What is the total number of orders?
2. What is the total sales revenue?
3. How do sales evolve over time?
4. Which products generate the highest sales?
5. Which product categories contribute the most to total sales?
Dashboard Features :
The dashboard provides an interactive overview of sales performance through key performance
indicators, visualizations, and dynamic filters.
Key Performance Indicators (KPIs)
KPI Value
Total Orders 1,000
Total Customers 1,000
Total Sales 815,000
Visualizations :
• Sales Over Time — Tracks how sales evolved throughout 2025.
• Total Sales by Product — Identifies the top-performing products.
• Sales by Product Category — Shows the contribution of each category to total sales.
• KPI Cards — Provide a quick overview of total orders, customers, and sales.
Interactive Features :
The dashboard includes interactive slicers that allow users to explore the data dynamically by:
• Order Date
• Product Category
• Country
These filters enable users to analyze sales performance from different perspectives.
Key Insights
Top-Performing Product :
Laptop was the top-performing product, generating approximately 220K in total sales.
Best-Performing Product Category
Electronics was the highest-performing product category, generating approximately 458K in sales and
contributing 56.16% of total sales.
Sales Trend :
Sales showed noticeable fluctuations throughout 2025, with several significant peaks and variations
over time.
Recommendations :
1. Focus on Electronics
Since Electronics generated the highest share of total sales (56.16%), this category appears to be
the main driver of sales performance.
Recommendation: Continue investing in and monitoring high-performing products within the
Electronics category.
2. Leverage Laptop Performance
The Laptop was identified as the top-performing product, generating approximately 220K in sales.
Recommendation: Further analyze the factors contributing to Laptop sales and explore opportunities
to replicate this performance across other products.
3. Investigate Sales Fluctuations
Sales showed noticeable variations throughout the year.
Recommendation: Analyze the reasons behind sales peaks and lower-performing periods to better
understand potential trends, customer behavior, or seasonal patterns.
4. Explore Performance Using Filters
The dashboard allows users to analyze sales by:
• Date
• Product Category
• Country
Recommendation: Use these filters to identify differences in sales performance across locations,
categories, and time periods.
Tools & Skills Used
Tools
• Power BI Desktop
• Power Query
• DAX
Skills Applied :
• Data Import
• Data Transformation
• Data Modeling
• Creating Relationships
• DAX Calculations
• Handling Missing Values
• Data Visualization
• Dashboard Design
• Interactive Filtering
• Sales Analysis

Project Highlights
• Built an interactive Sales Performance Dashboard using Power BI.
• Imported and analyzed customer and order data.
• Used Power Query to transform customer data.
• Used DAX and COALESCE() to handle missing values.
• Created a one-to-many relationship between Customers and Orders.
• Designed KPI cards and interactive visualizations.
• Identified top-performing products and categories.
• Applied interactive filters for deeper data exploration.
Learning Outcome
As my first hands-on Power BI project, this project helped me gain practical experience in:
• Building dashboards from raw datasets
• Working with Power Query transformations
• Writing basic DAX formulas
• Creating relationships between tables
• Designing interactive reports
• Extracting insights from sales data
This project represents an important step in my journey toward developing my skills in Business
Intelligence and Data Analytics.
Author
Ines Jendoubi
Business Intelligence Student | Aspiring Data Analyst
If you found this project interesting, feel free to explore the dashboard and connect with me on Link
