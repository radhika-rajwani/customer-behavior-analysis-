# 📊 Customer Shopping Behavior Analysis

![Project Workflow](./project_workflow.png)

## 🧠 Project Overview
This project analyzes customer shopping behavior using transactional data from **3,900 purchases** across various product categories.  
The objective is to uncover insights into **spending patterns, customer segments, product preferences, and subscription behavior** to support data-driven business decisions.

---

## 📂 Dataset Summary
- **Rows:** 3,900  
- **Columns:** 18  

### 🔑 Key Features:
- **Customer Info:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Behavior Metrics:** Discount Applied, Frequency of Purchases, Review Rating, Shipping Type  

### ⚠️ Missing Values:
- 37 missing values in **Review Rating** column  

---

## 🐍 Data Cleaning & EDA (Python)
- Loaded dataset using Pandas  
- Performed initial exploration using `df.info()` and `describe()`  
- Handled missing values using **group-wise median imputation**  
- Standardized column names (snake_case)  
- Feature engineering:
  - Created `age_group`
  - Created `purchase_frequency_days`  
- Removed redundant column (`promo_code_used`)  
- Loaded cleaned data into PostgreSQL  

---

## 🗄️ Data Analysis (SQL)
Performed analysis using PostgreSQL to answer key business questions:

- Revenue by gender  
- High-spending discount users  
- Top 5 products by rating  
- Shipping type comparison  
- Subscribers vs non-subscribers  
- Discount-dependent products  
- Customer segmentation (New, Returning, Loyal)  
- Top products per category  
- Repeat buyers vs subscriptions  
- Revenue by age group  

---

## 📊 Dashboard (Power BI)
Developed an **interactive dashboard** to visualize:
- Revenue trends  
- Customer behavior  
- Product performance  
- Segmentation insights  

---

## 💡 Business Recommendations
- Promote subscription plans with exclusive benefits  
- Introduce loyalty programs for repeat customers  
- Optimize discount strategies to maintain profit margins  
- Highlight top-performing products in marketing  
- Target high-value customer segments  

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)  
- PostgreSQL  
- SQL  
- Power BI  


