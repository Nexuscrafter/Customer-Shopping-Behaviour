# 📊 Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across multiple product categories.

The objective was to extract actionable insights into:
- Revenue patterns
- Customer segmentation
- Product performance
- Subscription behavior
- Discount sensitivity

The analysis combines **Python (Pandas)** for data preprocessing, **PostgreSQL** for structured business analysis, and **Power BI** for interactive visualization.

---

## 🗂 Dataset Summary

- **Total Records:** 3,900  
- **Total Features:** 18  
- **Missing Values:** 37 values in `review_rating` (handled via category-wise median imputation)

### Key Attributes:
- Customer demographics (age, gender, location, subscription_status)
- Purchase details (item_purchased, category, purchase_amount, season, size, color)
- Behavioral metrics (discount_applied, previous_purchases, frequency_of_purchases, shipping_type)

---

## 🛠 Tech Stack

- **Python**
- **Pandas**
- **PostgreSQL**
- **Power BI**

---

## 🔄 Project Workflow

### 1️⃣ Data Cleaning & Feature Engineering (Python)

- Loaded dataset using Pandas
- Performed exploratory analysis using `.info()` and `.describe()`
- Handled missing values in `review_rating` using category-wise median
- Standardized column names to snake_case
- Engineered new features:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant columns
- Exported cleaned dataset to PostgreSQL

---

### 2️⃣ Business Analysis (SQL)

Executed analytical SQL queries to answer business-critical questions:

- Revenue by gender
- High-spending discount users
- Top 5 products by rating
- Shipping type comparison (Standard vs Express)
- Subscriber vs Non-subscriber revenue comparison
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Revenue contribution by age group
- Repeat buyers vs subscription correlation

---

## 📊 Dashboard (Power BI)

Developed an interactive dashboard visualizing:

- Total Customers: **3.9K**
- Average Purchase Value: **$59.76**
- Average Review Rating: **3.75**
- Revenue by Category
- Revenue by Age Group
- Subscription Distribution
- Sales by Shipping Type

---

## 🔍 Key Insights

- Loyal customers form the majority of the customer base.
- Express shipping users show slightly higher average purchase values.
- Certain products demonstrate ~50% discount dependency.
- Young adults contribute the highest total revenue.
- Subscription users do not significantly outperform non-subscribers in average spend, indicating potential optimization opportunities.

---

## 💡 Business Recommendations

- Strengthen subscription benefits to improve conversion.
- Optimize discount strategy to balance sales growth and margin protection.
- Target high-revenue age groups with personalized marketing.
- Promote top-rated and best-selling products in campaigns.

---

## 🚀 Future Improvements

- Customer Lifetime Value (CLV) prediction
- Advanced customer clustering
- Product recommendation system
- Cloud deployment of dashboard

---

## 👤 Author

**Shourya Bhattacharyya**  
Full Stack Developer | Data Analytics Enthusiast
