Cafe Sales EDA & Business Intelligence Dashboard
Project Overview
This project focuses on analyzing cafe sales data using Python, SQL, and Power BI. The objective is to perform Exploratory Data Analysis (EDA), answer business questions using SQL, and build an interactive dashboard to uncover trends, customer behavior, and revenue insights.
Dataset
The dataset contains 10,000 cafe transactions with the following attributes:

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

Objectives

Perform descriptive statistical analysis.
Analyze distributions of numerical and categorical variables.
Answer business questions using SQL queries.
Identify relationships between variables using correlation analysis.
Build a Power BI dashboard for business insights.

Tools & Technologies

Python
Pandas
Matplotlib
Seaborn
SQLite
Jupyter Notebook
Power BI
GitHub

Exploratory Data Analysis (EDA)
Descriptive Statistics

Summary statistics for numerical features.
Dataset structure and data type verification.
Distribution analysis of spending and quantity purchased.

Univariate Analysis

Item Sales Distribution
Payment Method Distribution
Customer Spending Distribution
Transaction Frequency Analysis

Multivariate Analysis

Correlation Heatmap
Scatter Plot (Quantity vs Total Spending)
Revenue Analysis by Product

SQL Business Questions
1. Which item generates the highest revenue?
Analyzed product-wise revenue contribution.
2. What is the monthly revenue trend?
Evaluated sales performance across months.
3. Which payment method is most frequently used?
Identified customer payment preferences.
4. Which location generates the highest revenue?
Compared revenue across different sales locations.
5. Which item is ordered most frequently?
Determined the most popular menu item.
6. What is the average transaction value?
Calculated average customer spending.
7. What are the overall sales trends?
Analyzed transaction patterns and revenue growth.
Dashboard Components
KPI Cards

Total Revenue
Total Transactions
Average Spending
Top Revenue Item

Visualizations

Revenue by Item
Monthly Revenue Trend
Payment Method Distribution
Revenue by Location
Sales Performance Overview

Key Insights

Juice was the most frequently ordered item.
Salad generated the highest revenue among all products.
Quantity purchased shows a strong positive relationship with total spending.
Price per unit contributes significantly to revenue generation.
Customer spending is concentrated around low and medium transaction values.
Sales performance varies across locations and time periods.

Project Structure
Cafe-Sales-EDA/
│
├── cleaned_cafe_sales.csv
├── eda.ipynb
├── business_queries.sql
├── README.md
├── dashboard.png
└── CafeSalesDashboard.pbix

How to Run

Clone the repository.
Install required libraries:

pip install pandas matplotlib seaborn jupyter


Open the Jupyter Notebook:

jupyter notebook


Run all notebook cells.
Open the Power BI dashboard file (CafeSalesDashboard.pbix) to explore visualizations.

Conclusion
This project demonstrates how Python, SQL, and Power BI can be integrated to perform end-to-end business analytics. The analysis provides valuable insights into customer purchasing behavior, product performance, payment preferences, and revenue trends. These findings can support data-driven decision-making and business growth.
