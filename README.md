# 📊 Customer Shopping Behavior Analysis

### *End-to-End Data Analytics Project using Python, SQL & Power BI*

---

## 🚀 **Project Overview**

This project analyzes customer shopping behavior for a retail business using **Python (Pandas)** for data cleaning, **MySQL** for analytical querying, and **Power BI** for interactive dashboarding.
The goal is to uncover insights about customer demographics, revenue drivers, subscription impact, category performance, and purchasing patterns.

This end-to-end project demonstrates real-world data analytics skills used in industry.

---

## 🎯 **Business Problem**

The retail company wants to understand:

* Which customer groups generate the most revenue
* Which product categories perform best
* How subscription status affects spending
* How demographics influence purchases
* Which products drive customer satisfaction
* Whether discount strategies are effective

These insights help improve marketing, pricing, inventory planning, and customer retention.

---

## 📁 **Project Workflow**

The complete workflow includes:

1. **Data Understanding & Cleaning (Python / Pandas)**
2. **Feature Engineering (Age groups, purchase frequency, etc.)**
3. **MySQL Database Integration & SQL Analytics**
4. **Power BI Dashboard Development**
5. **Insights & Business Recommendations**

This simulates how analytics is performed in real corporate environments.

---

## 🧹 **1. Data Cleaning & Transformation (Python / Pandas)**

Key tasks performed:

* Handled missing values (category-wise imputation for Review Rating)
* Standardized column names
* Created new features:

  * `age_group`
  * `purchase_frequency_days`
* Dropped redundant column (`promo_code_used`)
* Uploaded cleaned dataset into MySQL database

📌 *Full Python code is included inside the project folder.*

---

## 🗄️ **2. SQL Business Analysis**

Advanced SQL queries were used to answer real business questions:

* Revenue by gender
* Above-average spenders using discounts
* Top 5 products by review rating
* Avg spend by shipping type
* Subscription vs non-subscription spending
* Customer segmentation (New, Returning, Loyal)
* Top 3 products per category (window functions)
* Revenue by age group
* Repeat buyers vs subscription rate

📌 SQL file included: `customer_behavior.sql`

---

## 📊 **3. Power BI Dashboard**

An interactive Power BI dashboard was created featuring:

### **📌 KPI Cards**

* Total Customers
* Average Purchase Amount
* Average Review Rating

### **📌 Visualizations**

* Donut Chart → Subscription Status
* Bar Chart → Revenue by Category
* Bar Chart → Sales by Category
* Clustered Bar Chart → Revenue by Age Group
* Clustered Bar Chart → Sales by Age Group

### **📌 Slicers**

* Subscription Status
* Gender
* Category
* Shipping Type

📌 PBIX file: `customer_behavior_dashboard.pbix`

---

## 🔍 **4. Key Insights**

* **Middle-aged customers generate the highest revenue.**
* **Clothing** leads in both revenue and sales volume.
* **Subscribed customers spend more** than non-subscribers.
* **Express shipping** is preferred by higher-value shoppers.
* Products like **Blouse, Jeans, and Sneakers** perform strongly.
* **Discounts significantly influence purchase decisions.**

---

## 💼 **5. Business Recommendations**

✔ **Expand Clothing inventory** due to high revenue potential.
✔ **Target middle-aged customers** through personalized promotions.
✔ **Enhance subscription program** (exclusive discounts, free shipping).
✔ **Optimize discount strategies** for categories with high responsiveness.
✔ **Promote express shipping** to increase high-value orders.
✔ **Run seasonal campaigns** based on shopping frequency trends.

---

## 🛠️ **Tech Stack**

| Tool                | Purpose                       |
| ------------------- | ----------------------------- |
| **Python (Pandas)** | Data cleaning & preprocessing |
| **MySQL**           | Analytical SQL queries        |
| **SQLAlchemy**      | Database integration          |
| **Power BI**        | Data visualization            |
| **ReportLab**       | Documentation PDF generation  |

---

## 📦 **Project Structure**

```
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── customer_analysis.ipynb
├── sql/
│   └── customer_behavior.sql
├── dashboard/
│   └── customer_behavior_dashboard.pbix
├── reports/
│   └── Customer_shopping_behavior_analysis.pdf
└── README.md  (this file)

