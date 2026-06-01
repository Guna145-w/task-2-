# Cafe Sales EDA & Business Intelligence Project

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) and Business Intelligence on a Cafe Sales dataset containing 10,000 transactions. The objective is to identify patterns, trends, and relationships within the data and generate meaningful business insights using statistical analysis, SQL queries, and dashboard visualizations.

---

## Objectives

- Perform descriptive statistical analysis on sales data.
- Explore customer purchasing patterns and sales trends.
- Answer business questions using SQL queries.
- Identify relationships between variables through correlation analysis.
- Build an interactive dashboard using Power BI.
- Generate actionable business insights for decision-making.

---

## Dataset Information

The dataset contains transaction-level information from a cafe.

### Dataset Features

| Column Name | Description |
|------------|-------------|
| transaction_id | Unique transaction identifier |
| item | Product purchased |
| quantity | Quantity purchased |
| price_per_unit | Price per unit of item |
| total_spent | Total amount spent in transaction |
| payment_method | Mode of payment |
| location | Sales location |
| transaction_date | Date of transaction |
| month | Month of transaction |
| day_name | Day of the week |

### Dataset Summary

- Total Records: 10,000
- Total Features: 10
- Data Type: Structured CSV Data

---

## Tools & Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- SQLite
- Jupyter Notebook
- VS Code
- Power BI

---

# Exploratory Data Analysis (EDA)

The following analyses were performed:

## 1. Dataset Overview

- Loaded dataset using Pandas
- Examined dataset structure
- Checked data types and record count

## 2. Descriptive Statistics

Calculated:

- Mean
- Median
- Standard Deviation
- Minimum Values
- Maximum Values
- Quartiles

## 3. Univariate Analysis

Performed:

### Product Analysis

- Item frequency distribution
- Most ordered products

### Spending Analysis

- Distribution of total spending
- Customer spending behavior

### Payment Method Analysis

- Payment method frequency distribution

---

# Data Visualization

The following visualizations were created:

## Histogram

- Distribution of Total Spending

## Bar Charts

- Revenue by Item
- Payment Method Distribution
- Revenue by Location

## Line Chart

- Monthly Revenue Trend

## Correlation Heatmap

- Relationship between Quantity, Price per Unit, and Total Spending

## Scatter Plot

- Quantity vs Total Spending

---

# SQL Business Questions

The following SQL queries were written and executed:

### 1. Which item generates the highest revenue?

```sql
SELECT item,
SUM(total_spent) AS revenue
FROM cafe_sales
GROUP BY item
ORDER BY revenue DESC;
```

### 2. What is the monthly revenue trend?

```sql
SELECT month,
SUM(total_spent) AS revenue
FROM cafe_sales
GROUP BY month;
```

### 3. Which payment method is used most frequently?

```sql
SELECT payment_method,
COUNT(*) AS transactions
FROM cafe_sales
GROUP BY payment_method;
```

### 4. Which location generates the highest revenue?

```sql
SELECT location,
SUM(total_spent) AS revenue
FROM cafe_sales
GROUP BY location;
```

### 5. Which item is ordered most frequently?

```sql
SELECT item,
COUNT(*) AS orders
FROM cafe_sales
GROUP BY item
ORDER BY orders DESC;
```

### 6. What is the average transaction value?

```sql
SELECT AVG(total_spent)
FROM cafe_sales;
```

### 7. What are the overall sales trends across months?

```sql
SELECT month,
SUM(total_spent)
FROM cafe_sales
GROUP BY month;
```

---

# Power BI Dashboard

A Business Intelligence dashboard was developed using Power BI.

## Dashboard Components

### KPI Cards

- Total Revenue
- Total Transactions
- Average Spending
- Top Revenue Item

### Visualizations

- Revenue by Item
- Monthly Revenue Trend
- Payment Method Distribution
- Revenue by Location

The dashboard provides a quick overview of sales performance and customer behavior.

---

# Key Insights

- Juice was the most frequently ordered item.
- Salad generated the highest revenue among all products.
- Quantity purchased has a strong positive correlation with total spending.
- Price per unit significantly influences overall revenue.
- Customer spending is concentrated around low and medium transaction values.
- Different locations contribute differently to total sales performance.
- Monthly sales trends help identify peak business periods.

---

# Project Structure

```text
Cafe_Sales_EDA/
│
├── cleaned_cafe_sales.csv
├── eda.ipynb
├── business_queries.sql
├── README.md
├── dashboard.png
└── CafeSalesDashboard.pbix
```

---

# Conclusion

This project successfully applied Exploratory Data Analysis (EDA) and Business Intelligence techniques to analyze a Cafe Sales dataset containing 10,000 transactions. Statistical analysis, SQL-based business queries, and interactive visualizations were used to uncover meaningful patterns and trends in customer purchasing behavior.

The analysis revealed that Juice was the most frequently ordered item, while Salad generated the highest revenue. Correlation analysis showed a strong positive relationship between quantity purchased and total spending, indicating that larger purchases contribute significantly to revenue growth. Payment methods, locations, and monthly sales trends were also examined to better understand business performance.

The Power BI dashboard provides a clear and interactive view of key performance indicators, enabling efficient monitoring of sales performance and customer behavior.

Overall, this project demonstrates how data analytics and business intelligence tools can be used to transform raw transactional data into actionable insights that support data-driven business decisions.
