# 📊 Global Superstore Sales Analytics | Power BI Project
End-to-end Power BI project analyzing Global Superstore retail data using star schema modeling, DAX-driven KPIs, and interactive dashboards, including profit root-cause analysis with a decomposition tree.

## 📊 Project Overview

This project presents an end-to-end Power BI analytics solution built on the Global Superstore retail dataset.
The objective is to analyze sales performance, profitability, and business drivers using clean data modeling, KPI design, and interactive dashboards.

The project moves beyond descriptive reporting by applying root-cause analysis through a Profit Decomposition Tree, enabling stakeholders to understand why profit changes, not just what happened.

## 🎯 Project Objectives

- Provide a high-level executive view of business performance
- Identify key revenue and profit drivers across regions, products, and customer segments
- Perform profit root-cause analysis using decomposition techniques
- Demonstrate best practices in Power BI data modeling and DAX
- Deliver actionable insights for strategic decision-making

## 🗂️ Data Description

- Dataset: Global Superstore Sales Data
- Industry: Retail / Supply Chain
- Records: 50,000+ transactions
- Data Model: Star Schema

### Tables Used

- Fact_Orders: Sales, profit, quantity, discount, order & ship dates
- Dim_Customers: Customer details, segment, geography
- Dim_Products: Product, category, sub-category
- Dim_Geography: Region, market, country, state, city
A surrogate key (Geo_ID) was created to ensure geographic uniqueness and clean relationships.

## 🧹 Data Preparation & Modeling (Summary)

- Cleaned and transformed data using Power Query
- Removed duplicate and redundant columns
- Standardized data types and handled missing values
- Designed a Star Schema with one-to-many relationships
- Optimized model performance using single-direction filtering


## 🔍 Key Insights

- The Central region is the largest contributor to overall profit
- The Technology category generates the highest profit among all categories
- Copiers and Phones are the strongest profit-driving sub-categories
- The Consumer segment contributes the maximum share of profit
- Overall business performance shows a consistent upward trend in sales and profit
- These insights help prioritize high-margin products, regions, and customer segments.

## 🛠️ Skills Demonstrated

- Data cleaning and transformation (Power Query)
- Dimensional data modeling (Star Schema)
- DAX for KPI creation and time-intelligence calculations
- Dashboard design and data storytelling
- Root-cause analysis using Decomposition Tree
- Business-focused insight generation

## 🧰 Tools & Technologies Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling (Star Schema)
- Interactive Visualizations

## 📸 Screenshots

## 📌 Dashboard 1: Profit Decomposition & Root Cause Analysis
Key Insight: Profit is primarily driven by the Central region, with the Technology category contributing the highest share. Within Technology, Copiers and Phones generate maximum profit, especially from the Consumer segment, indicating a strong opportunity to focus on high-margin products and customer groups.
![](https://github.com/Harshad820/Global_Superstore_Insights/blob/main/dashboards/7.png)

## 📌 Dashboard 2: Executive Overview Dashboard
Key Insight: The business shows a consistent upward trend in sales and profit over time. The Consumer segment contributes the largest share of revenue, while the Central and South regions lead in overall sales, highlighting stable growth and strong regional performance.
![](https://github.com/Harshad820/Global_Superstore_Insights/blob/main/dashboards/1.png)
