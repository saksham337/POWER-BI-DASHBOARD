![power bi](https://github.com/user-attachments/assets/82e26db9-1ac6-42b4-9112-eee3e1d8991c)
📊 Global Superstore Sales Insights
Business Intelligence Project using Power BI, DAX & Data Visualization

This project presents an end-to-end Business Intelligence solution built on the Global Superstore dataset. The Power BI dashboard provides interactive analytics across 22K+ orders, enabling data-driven insights into sales performance, profitability, customer trends, and forecasting.

🚀 Project Overview

The goal of this project is to convert raw transactional data into actionable business insights.
Using Power BI, custom DAX measures, and advanced visualizations, the dashboard answers key business questions related to:

Regional and category-wise sales performance

Profitability trends

Customer segments and order patterns

Shipping efficiency

Forecasting future sales based on historical trends

🛠️ Tech Stack

Power BI Desktop

Power Query (ETL)

DAX (Data Analysis Expressions)

Data Modeling

Visualization & Dashboard Design

📁 Dataset Description

The dataset contains:

22,000+ orders

Sales, profit, quantity, discounts

Customer demographics

Product category & sub-category

Regional and shipping information

Order & ship dates

Dataset Source: Global Superstore sample dataset

🔍 Key Features of the Dashboard
✔️ 1. KPIs & Overview Metrics

Total Sales: $1.6M

Total Profit: $175K

Total Orders: 22K+

Average Shipping Time: 4 days

✔️ 2. Interactive Visuals

Region-wise performance (Maps, Bar Charts)

Category & sub-category analysis

Payment modes & customer segment insights

Time-series trends with dynamic slicers

✔️ 3. Forecasting

Implemented a 15-day sales forecast using Power BI’s time-series analytics.

Helps anticipate short-term demand and business planning.

✔️ 4. Drill-down Functionality

Region → Category → Sub-category → Product

Date hierarchy drill (Year → Quarter → Month → Day)

✔️ 5. Dynamic Filters & Slicers

Region

Category

Customer Segment

Payment Mode

Ship Mode

📈 Key Insights Generated
Insight	Value
Top Performing Region	West region contributes 33% of sales
Most Used Payment Mode	Cash on Delivery (43%)
Top Sub-category	Phones generate $0.28M
Average Shipping Time	4 days
🧮 Custom DAX Measures Used

Some examples:

Total Sales = SUM(Orders[Sales])

Total Profit = SUM(Orders[Profit])

Avg Shipping Time = AVERAGE(Orders[Ship Days])

Sales Forecast = FORECAST.LINEAR([Date], [Total Sales], [Order Date]) 🧩 Data Model

The model follows a Star Schema:

Fact Table → Orders

Dimension Tables → Customers, Products, Regions, Calendar

This improves performance and enables efficient DAX calculations.
