The goal of this project is to understand customer ordering behavior, identify top-selling pizza types, and evaluate overall business performance.
The dashboard highlights key KPIs and visualizations that help stakeholders makFile	Description
Pizza_Sales_Dashboard.pbix - Power BI interactive dashboard
Dashboard_Screenshots/	Image previews of the dashboard

📊 Key Metrics (KPIs)

Total Revenue

Total Orders

Total Pizzas Sold

Average Order Value (AOV)

Average Pizza per Order

📈 Insights & Visualizations
1. Top 5 Pizza Types by Quantity Ordered

Displays the most popular pizza categories and helps identify customer preferences.

2. Sales Trend Analysis

Reveals how revenue and order volume change over time.

3. Order Distribution

Breakdown of orders by hour, weekday, or month (depending on your setup).

4. Revenue by Category / Size

Shows how different pizza sizes or categories contribute to total sales.

🧮 DAX Measures Used (Examples)
Total Revenue = SUM('OrderDetails'[Revenue])

Total Orders = DISTINCTCOUNT('Orders'[OrderID])

Average Order Value = [Total Revenue] / [Total Orders]

Total Pizzas Sold = SUM('OrderDetails'[Quantity])

🛠️ Tools Used

Microsoft Excel – data cleaning & preprocessing

Power BI Desktop – modeling, DAX, and dashboard creation

GitHub – project hosting & version control

📘 What I Learned

Building a star schema data model

Creating analytical measures using DAX

Designing clean and insight-driven dashboards

Transforming raw data into actionable business intelligence

👤 About the Project

This project was created to showcase data analytics and dashboard development skills suitable for roles such as:

Data Analyst

Business Intelligence Analyst

Excel/Power BI Analyst

Reporting Analyste informed decisions.
