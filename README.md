# 🛍️ Customer Shopping Behavior Analysis

## 📌 Project Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into purchasing patterns, customer segmentation, product performance, and revenue trends. The objective is to support data-driven business decisions through data analysis and visualization.

---

## 📊 Dataset Summary

* **Total Records:** 3,900+ transactions
* **Features:** 18 columns
* **Data Includes:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Product, Category, Amount, Season, Size, Color)
  * Behavioral metrics (Discount usage, Purchase frequency, Ratings, Shipping type)
* **Missing Values:** Handled in *Review Rating* column using median imputation

---

## 🧹 Data Cleaning & Preparation (Python)

* Loaded and explored dataset using **Pandas**
* Handled missing values using **median imputation**
* Standardized column names for consistency
* Created new features:

  * `age_group` for segmentation
  * `purchase_frequency_days` for behavior analysis
* Removed redundant columns (e.g., promo_code_used)
* Ensured data consistency and quality

---

## 🗄️ Database Integration (PostgreSQL)

* Imported cleaned dataset into **PostgreSQL**
* Structured data for efficient querying and analysis
* Used advanced SQL techniques:

  * Joins, CTEs, Window Functions, Aggregations

---

## 🔍 Business Analysis (SQL)

Key insights derived:

* Revenue analysis by **gender and age group**
* Identification of **high-spending customers using discounts**
* **Top-rated and best-selling products**
* Comparison of **shipping types (Standard vs Express)**
* **Customer segmentation:** New, Returning, Loyal
* Impact of **subscription status on revenue**
* Identification of **discount-dependent products**
* Analysis of **repeat buyers and subscription behavior**

---

## 📈 Dashboard (Power BI)

* Developed an **interactive dashboard** to visualize:

  * Sales performance
  * Customer segments
  * Product insights
  * Revenue trends
* Enabled easy tracking of KPIs and business metrics

---

## 💡 Business Recommendations

* Improve **customer retention** through loyalty programs
* Increase **subscriptions** with exclusive benefits
* Optimize **discount strategies** to balance profit and sales
* Focus on **high-performing products and categories**
* Implement **targeted marketing** based on customer segments

---

## 🛠️ Tools & Technologies

* **Python:** Pandas, NumPy
* **SQL:** PostgreSQL
* **Visualization:** Power BI
* **Excel:** Data Analysis

---

## 📌 Key Outcomes

* Extracted actionable insights from **3,900+ transactions**
* Improved understanding of **customer behavior and revenue drivers**
* Built an end-to-end data analysis pipeline from **data cleaning → SQL → dashboard**



