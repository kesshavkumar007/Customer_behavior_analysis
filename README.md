# 🛍️ Customer Shopping Behavior Analysis

An end-to-end data analytics project that explores customer shopping patterns using transactional purchase data.  
The project combines **Python**, **PostgreSQL (SQL)**, and **Power BI** to generate actionable business insights.

---

## 📌 Project Overview

This project analyzes customer behavior across **3,900 purchase transactions** to uncover:

- Spending trends  
- Customer segmentation  
- Product and category performance  
- Discount and subscription behavior  
- Revenue contribution across demographics  

The goal is to support data-driven decision-making for marketing, sales, and customer retention strategies.

---

## 📊 Dataset Information

- **File:** `customer_shopping_behavior.csv`
- **Rows:** 3,900  
- **Columns:** 18  

### Key Features:

- Customer Demographics: Age, Gender, Location, Subscription Status  
- Purchase Details: Category, Item Purchased, Amount, Season, Size, Color  
- Shopping Behavior: Discounts, Previous Purchases, Review Ratings, Shipping Type  

### Data Quality:

- 37 missing values in the `Review Rating` column  
- Missing values handled using **median imputation by product category**

---

## 🧹 Data Cleaning & Feature Engineering (Python)

Performed in the Jupyter notebook:

📌 `customer_shopping_behaviour.ipynb`

Key steps:

- Data exploration using `info()` and `describe()`
- Null value handling and imputation
- Column renaming to snake_case
- Feature engineering:
  - `age_group`
  - Purchase frequency metrics
- Removed redundant columns
- Loaded cleaned dataset into PostgreSQL for SQL-based analysis

---

## 🛠️ SQL Business Analysis (PostgreSQL)

SQL queries are available here:

📌 `customer_behavior.sql`

Business questions answered:

- Revenue by gender  
- High-spending discount users  
- Top-rated products  
- Express vs Standard shipping spend comparison  
- Subscribers vs Non-subscribers revenue trends  
- Discount-dependent products  
- Customer segmentation (New / Returning / Loyal)  
- Revenue contribution by age group  

---

## 📈 Power BI Dashboard

Interactive dashboard built to visualize key insights:

📌 `customer_behavior_analysis_dashboard.pbix`

Dashboard highlights:

- Revenue trends by customer segment  
- Category-level sales performance  
- Subscription impact on spending  
- Discount usage patterns  
- Demographic-based revenue distribution  

---

## 📄 Project Report

A detailed project summary and findings are documented in:

📌 `Customer_shopping_behavior_report.pdf`

This report includes:

- Data preparation steps  
- SQL insights  
- Dashboard summary  
- Business recommendations  

---

## 💡 Business Recommendations

- Boost subscription programs through exclusive benefits  
- Introduce loyalty rewards for repeat customers  
- Optimize discount strategies to balance margins  
- Promote top-rated products in marketing campaigns  
- Target high-revenue age groups and premium shipping users  

---

## 🧰 Tools & Technologies Used

- **Python** (Pandas, NumPy)
- **SQL** (PostgreSQL)
- **Power BI**
- **Excel** (initial exploration)

---

## 📂 Project Structure

Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── customer_shopping_behaviour.ipynb
├── customer_behavior.sql
├── customer_behavior_analysis_dashboard.pbix
├── Customer_shopping_behavior_report.pdf
└── README.md



---

## 🚀 Future Enhancements

- Predict customer churn using machine learning
- Automate Power BI refresh with live database connection
- Advanced segmentation using clustering techniques

---

## 👤 Author

**Keshav Kumar**  
Data Analytics Enthusiast | SQL • Python • Power BI  

Feel free to connect or collaborate!

