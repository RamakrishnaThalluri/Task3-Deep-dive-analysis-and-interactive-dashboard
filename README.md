📊 Task 3 – Deep Dive Analysis & Interactive Dashboard
Amazon Sales Data Analysis
📌 Project Overview

This project is part of my Data Analyst Internship – Task 3, focused on performing a deep-dive business analysis and building an interactive Power BI dashboard using Amazon Sales Data.

The objective of this task is to:

Define core business KPIs

Perform advanced profitability and regional analysis

Build an interactive dashboard

Generate actionable business insights

🎯 Objective

To analyze Amazon sales performance across regions, item types, and sales channels, and provide strategic business insights using data visualization and KPI tracking.

📂 Dataset Description

The dataset contains global Amazon sales transactions with the following fields:

Region

Country

Item Type

Sales Channel (Online / Offline)

Order Priority

Order Date

Ship Date

Units Sold

Unit Price

Unit Cost

Total Revenue

Total Cost

Total Profit

📊 Core KPIs Defined
1️⃣ Total Revenue

Formula:
SUM(Total Revenue)

Meaning:
Total income generated from sales.

2️⃣ Total Profit

Formula:
SUM(Total Profit)

Meaning:
Net earnings after deducting total cost from revenue.

3️⃣ Profit Margin %

Formula (DAX):

Profit Margin % = 
DIVIDE(SUM(AmazonSalesData[Total Profit]),
       SUM(AmazonSalesData[Total Revenue])) * 100

Meaning:
Percentage of revenue retained as profit.

4️⃣ Average Selling Price (ASP)
Average Selling Price =
DIVIDE(SUM(AmazonSalesData[Total Revenue]),
       SUM(AmazonSalesData[Units Sold]))

Meaning:
Average price per unit sold.

5️⃣ Average Shipping Days
Shipping Days =
DATEDIFF(AmazonSalesData[Order Date],
         AmazonSalesData[Ship Date],
         DAY)
Avg Shipping Days =
AVERAGE(AmazonSalesData[Shipping Days])

Meaning:
Average time taken to ship orders.

🔍 Deep Dive Analysis
1️⃣ Regional Profitability Analysis

Compared revenue and profit across regions

Identified high-revenue vs high-margin regions

Analyzed performance gaps

📌 Insight Example:

Europe generated highest revenue.

Sub-Saharan Africa showed lower profit margins.

2️⃣ Item Type Profitability Analysis

Compared profit by product category

Identified most profitable item types

Analyzed high-sales but low-margin products

📌 Insight Example:

Cosmetics and Household categories generated strong profit.

Some categories showed high revenue but lower margins.

3️⃣ Sales Channel Comparison

Compared Online vs Offline sales

Measured revenue and profitability differences

📌 Insight Example:

Online channel generated higher profit margin.

Offline channel had stable but lower margin performance.

📈 Dashboard Features

The Power BI dashboard includes:

✔ KPI Cards (Revenue, Profit, Margin, Shipping Days)
✔ Revenue by Item Type
✔ Profit by Region
✔ Sales Channel Comparison
✔ Country-Level Map Visualization
✔ Interactive Filters (Region, Item Type, Sales Channel, Date)

🛠 Tools & Technologies Used

Python (Exploratory Data Analysis)

Power BI (Interactive Dashboard)

DAX (Advanced Measures)

Excel (Data Preparation)

GitHub (Project Documentation)

💡 Key Business Insights

Total Revenue: 137.35M

Total Profit: 44.17M

Profit Margin: ~32%

Europe leads in revenue contribution

Cosmetics category contributes highest profit

Online channel performs better in profitability

Average shipping duration is approximately X days

(Update with exact numbers from your dashboard)

📷 Dashboard Preview

<img width="1507" height="841" alt="Screenshot 2026-03-03 115311" src="https://github.com/user-attachments/assets/0cafcce3-3b82-4984-8cf4-e9bf7da341d6" />


Example:

![Dashboard Preview](screenshot.png)
🚀 Project Outcome

This project demonstrates:

KPI identification and business metric tracking

Deep-dive profitability analysis

Advanced DAX implementation

Interactive dashboard development

Business insight generation

📌 Conclusion

This deep-dive analysis provides a clear understanding of:

Regional performance

Product profitability

Channel efficiency

Operational efficiency

The interactive dashboard enables decision-makers to explore insights dynamically and make data-driven strategic decisions.

🔗 Author

Ramakrishna Thalluri
Data Analyst Intern
Skilled in Python, SQL, Power BI, and Data Visualization
