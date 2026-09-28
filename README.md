🛒 Blinkit Sales & Business Analytics Dashboard

An interactive Power BI dashboard developed to analyze Blinkit's sales performance, product categories, outlet performance, customer ratings, and business trends.

The project transforms raw data into meaningful business insights using Power Query, DAX, data modeling, and interactive Power BI visualizations.

📌 Project Overview

The Blinkit Sales & Business Analytics Dashboard provides a comprehensive view of business performance through interactive reports and KPIs.

The dashboard helps analyze:

💰 Overall sales performance
📦 Product and item performance
🏪 Outlet-wise sales
📍 Location-wise performance
⭐ Customer ratings
📊 Product category trends
📈 Sales trends over time

The goal is to make business data easier to understand and support data-driven decision-making.

🎯 Project Objectives
Analyze Blinkit's overall sales performance.
Identify high-performing product categories.
Compare different outlet types and sizes.
Analyze sales based on outlet locations.
Understand customer rating patterns.
Create interactive KPIs and visualizations.
Convert raw data into actionable business insights.
🛠️ Tools & Technologies
Tool / Technology	Purpose
Power BI	Dashboard development & visualization
Power Query	Data cleaning & transformation
DAX	Measures and KPI calculations
Excel / CSV	Source dataset
Data Modeling	Organizing data for analysis
📂 Dataset

The dataset contains information related to products, sales, ratings, and outlets.

Main attributes include:
Item Type
Item Weight
Item Visibility
Item MRP
Sales
Rating
Outlet Identifier
Outlet Type
Outlet Size
Outlet Location Type
Outlet Establishment Year
🔄 Project Workflow
Raw Dataset
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Interactive Visualizations
     ↓
Business Insights
🧹 Data Preparation

Data preparation was performed using Power Query.

Key steps included:

Handling missing values
Correcting data types
Cleaning inconsistent values
Removing unnecessary columns
Transforming columns
Preparing data for visualization
📊 Dashboard Features
KPI Cards

The dashboard includes important KPIs such as:

Total Sales
Total Items
Average Rating
Outlet Count
Sales Analysis

The dashboard analyzes sales based on:

Item Type
Outlet Type
Outlet Size
Outlet Location
Establishment Year
Interactive Filters

Users can dynamically filter the dashboard using slicers such as:

Outlet Type
Outlet Size
Location
Item Type
Year
Product Category
🧮 DAX Measures

Example measures used in the project:

Total Sales = SUM(Sales[Sales])
Total Items = COUNTROWS(Sales)
Average Rating = AVERAGE(Sales[Rating])

These measures help calculate important business KPIs dynamically.
📌 Project Tagline

“Turning Blinkit Data into Meaningful Business Insights.”
