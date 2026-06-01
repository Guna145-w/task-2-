Cafe Sales Analytics Dashboard
Project Overview
This project presents a comprehensive analysis of cafe sales data using Python, SQL, and Power BI. The primary objective is to explore customer purchasing behavior, identify sales trends, answer business-driven questions through SQL, and develop an interactive dashboard for data-driven decision-making.
Dataset Description
The dataset contains 10,000 cafe transactions and includes information related to products, sales, payment methods, locations, and transaction dates.
Features

Transaction ID
Item
Quantity
Price Per Unit
Total Spent
Payment Method
Location
Transaction Date
Month
Day Name

Project Objectives

Perform Exploratory Data Analysis (EDA) on cafe sales data.
Generate descriptive statistics and visualize data distributions.
Analyze customer purchasing patterns.
Solve business problems using SQL queries.
Explore relationships between variables through correlation analysis.
Design a Power BI dashboard to monitor key business metrics.

Technologies Used

Python
Pandas
Matplotlib
Seaborn
SQLite
Jupyter Notebook
Power BI
GitHub

Exploratory Data Analysis
Descriptive Statistics

Dataset overview
Summary statistics
Data type verification
Distribution analysis

Univariate Analysis

Product popularity analysis
Payment method distribution
Customer spending distribution
Transaction frequency analysis

Multivariate Analysis

Correlation heatmap
Scatter plot analysis
Revenue contribution analysis
Quantity versus spending relationship

SQL Business Questions
The following business questions were addressed:

Which product generates the highest revenue?
What is the monthly revenue trend?
Which payment method is used most frequently?
Which location contributes the highest revenue?
Which product is ordered most often?
What is the average transaction value?
What patterns can be observed in overall sales performance?

Dashboard Features
Key Performance Indicators (KPIs)

Total Revenue
Total Transactions
Average Spending per Transaction
Top Revenue-Generating Product

Visualizations

Revenue by Product
Monthly Revenue Trend
Payment Method Distribution
Revenue by Location
Sales Performance Overview

Key Findings

Juice is the most frequently purchased product.
Salad generates the highest overall revenue.
Customer spending increases significantly with higher purchase quantities.
Product pricing has a strong influence on total revenue.
Sales patterns vary across locations and months.
Most transactions fall within low to medium spending ranges.

Project Structure
Cafe-Sales-Analytics/
│
├── cleaned_cafe_sales.csv
├── eda.ipynb
├── business_queries.sql
├── README.md
├── dashboard.png
└── CafeSalesDashboard.pbix

How to Run the Project

Download or clone the repository.
Install the required Python libraries:

pip install pandas matplotlib seaborn jupyter


Open the Jupyter Notebook:

jupyter notebook


Run all notebook cells to reproduce the analysis.
Open the Power BI dashboard file (CafeSalesDashboard.pbix) to explore interactive visualizations.

Conclusion
This project demonstrates the practical application of data analytics, SQL querying, and business intelligence techniques on real-world sales data. The insights obtained can help improve inventory management, optimize product offerings, understand customer preferences, and support strategic business decisions.
