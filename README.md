# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using transactional retail data to uncover purchasing trends, customer preferences, loyalty patterns, and product performance.

The project demonstrates an end-to-end Data Analytics workflow using:

- Python (Data Cleaning & EDA)
- MySQL (Business Analysis)
- Power BI (Dashboarding)
- Git & GitHub (Version Control)

---

## Business Problem

A retail company wants to better understand customer purchasing behavior to improve:

- Customer Engagement
- Product Strategy
- Marketing Campaigns
- Revenue Growth
- Customer Retention

The objective is to identify key factors influencing customer decisions, including:

- Discounts
- Product Categories
- Review Ratings
- Shipping Preferences
- Subscription Status
- Age Demographics

---

## Dataset Information

### Records
- 3,900 Customer Transactions

### Features
- Customer ID
- Age
- Gender
- Location
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Season
- Color
- Size
- Review Rating
- Shipping Type
- Discount Applied
- Previous Purchases
- Frequency of Purchases

---

## Tools & Technologies

### Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLAlchemy
- PyMySQL

### Database
- MySQL

### Visualization
- Power BI

### Development
- Jupyter Notebook
- VS Code
- Git & GitHub

---

## Project Workflow

### 1. Data Preparation

- Imported dataset using Pandas
- Handled missing values
- Renamed columns using snake_case convention
- Performed data consistency checks
- Created age group segments

### 2. Database Integration

- Connected Python with MySQL using SQLAlchemy
- Loaded cleaned data into MySQL database
- Created tables for business analysis

### 3. SQL Analysis

Business questions answered:

1. Revenue by Gender
2. High-Spending Discount Users
3. Top 5 Products by Review Rating
4. Shipping Type Comparison
5. Subscribers vs Non-Subscribers Analysis
6. Discount-Dependent Products
7. Customer Segmentation
8. Top Products per Category
9. Repeat Buyers and Subscription Behavior
10. Revenue by Age Group

### 4. Dashboard Development

Built an interactive Power BI dashboard featuring:

- Customer Overview
- Revenue Analysis
- Subscription Insights
- Category Performance
- Age Group Analysis
- Product Performance
- Dynamic Filters

---

## Key Insights

### Revenue Analysis
- Male customers generated higher overall revenue than female customers.

### Product Ratings
Top-rated products include:
- Gloves
- Sandals
- Boots
- Hat
- Skirt

### Customer Loyalty
- Majority of customers belong to the Loyal segment.
- Repeat buyers significantly contribute to overall revenue.

### Shipping Analysis
- Express shipping users have a slightly higher average purchase amount.

### Subscription Analysis
- Subscribers show strong engagement potential despite lower overall population.

---

## Business Recommendations

### Increase Subscription Adoption
Offer exclusive discounts and loyalty benefits to subscribers.

### Reward Loyal Customers
Implement loyalty programs for repeat buyers.

### Optimize Discount Strategy
Use targeted discounts to improve profitability.

### Promote High-Performing Products
Feature top-rated products in marketing campaigns.

### Target High-Revenue Segments
Focus campaigns on age groups contributing the highest revenue.

---

## Dashboard Preview

The Power BI dashboard provides:

- Total Customers
- Average Purchase Amount
- Average Review Rating
- Revenue by Category
- Sales by Category
- Revenue by Age Group
- Subscription Distribution

---

## Folder Structure

```text
Customer_Shopping_Behavior_Analysis/
│
├── data/
├── notebooks/
├── sql/
├── dashboard/
├── reports/
├── problem_statement/
├── requirements.txt
└── README.md
```

---

## Author

**Laxman sannu Gouda**

Data Analyst | Python | SQL | Power BI
