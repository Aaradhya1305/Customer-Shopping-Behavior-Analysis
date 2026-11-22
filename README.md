# Customer Shopping Behavior Analysis

An end-to-end data analytics project focused on understanding customer purchasing patterns, product preferences, spending behaviour, discounts, and subscription trends using Python, MySQL, SQL, and Power BI.

## Project Overview

This project analyzes customer shopping behaviour using 3,900 records to identify purchasing patterns and generate meaningful business insights.

The project follows a complete data analytics workflow, from data cleaning and transformation to SQL analysis and interactive dashboard development.

## Tools & Technologies

- **Python:** Data cleaning and preprocessing
- **Pandas:** Data manipulation and analysis
- **Jupyter Notebook:** Exploratory data analysis
- **MySQL:** Database management
- **SQL:** Business analysis and querying
- **Power BI:** Interactive dashboard visualization

## Dataset Overview

The dataset contains 3,900 records and 18 original columns, covering customer demographics, product categories, purchase amounts, ratings, discounts, subscriptions, and shipping preferences.

Key attributes include:
- Customer ID, Age, Gender
- Item Purchased, Category, Purchase Amount
- Review Rating, Subscription Status
- Shipping Type, Discount Applied
- Previous Purchases, Payment Method
- Frequency of Purchases

## Project Workflow

### 1. Data Cleaning & Preprocessing
- Inspected dataset structure and data types.
- Handled missing review ratings using category-wise median imputation.
- Standardized column names using snake_case.
- Removed redundant columns.
- Checked data consistency.

### 2. Feature Engineering
- Created age groups using quantile-based segmentation.
- Converted purchase frequency categories into approximate day intervals.

### 3. Database Integration
- Connected Python with MySQL using SQLAlchemy.
- Created the `customer_behavior` database.
- Loaded the cleaned dataset into the `customer_table` table.

### 4. SQL Analysis
Performed 10 business-driven SQL queries covering:

- Revenue analysis by gender and age group.
- Discount usage and purchasing behaviour.
- Product ratings and popularity.
- Shipping method comparisons.
- Subscription analysis.
- Customer segmentation (New, Returning, Loyal).
- Top-performing products across categories.

SQL concepts used include:
`GROUP BY`, `JOIN`, `CASE`, Subqueries, CTEs, Aggregate Functions, and Window Functions.

### 5. Power BI Dashboard

Developed an interactive dashboard featuring:

- KPI Cards
- Revenue by Product Category
- Revenue by Age Group
- Subscription Status Distribution
- Customer Segmentation
- Interactive Slicers and Filters

### Dashboard Preview

![Customer Shopping Behavior Dashboard](dashboard.jpeg)

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Customer Shopping Behavior Data.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── Customer_Behavior_Analysis_SQL.sql
├── Customer_Shopping_Behavior_Expanded_Report.pdf
├── dashboard.jpeg
└── README.md
```

## Future Improvements

- Improve customer segmentation.
- Add time-based purchasing analysis.
- Include profit and revenue comparisons.
- Enhance dashboard interactivity.
- Explore customer retention patterns.