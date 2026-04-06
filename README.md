# 🛍️ Customer Behaviour & Revenue Analysis

## 🧩 Business Problem Statement

A leading retail company wants to better understand its customers’ shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty. The management team has observed changes in purchasing patterns across demographics, product categories, and sales channels.

The company aims to identify key factors influencing customer decisions, such as discounts, product reviews, seasonal trends, and purchasing preferences.

### 🎯 Key Business Question
**How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

## 🎯 Objectives
- Analyze customer demographics and purchasing behavior  
- Identify key revenue drivers  
- Evaluate the impact of discounts and subscriptions  
- Segment customers for better targeting  

## 📌 Project Overview
This project focuses on analyzing customer shopping behavior to derive insights on revenue trends, customer segmentation, and purchasing patterns using Python, SQL, and Power BI. 
The goal was to clean raw data, perform exploratory data analysis (EDA), and generate actionable insights through queries and visualization.


The project follows an **end-to-end analytics workflow**:
**Data Cleaning (Python) → Storage (MySQL) → Analysis (SQL) → Visualization (Power BI)**


---


## 📂 Dataset
- **File:** `customer_shopping_behavior.csv`
- Contains customer-level data including demographics, purchase patterns, and review ratings.

---

## ⚙️ Tech Stack
- **Python (Pandas)** → Data cleaning & EDA  
- **MySQL** → Data storage & analysis  
- **SQLAlchemy** → Database connection  
- **Power BI** → Dashboard & visualization  

---

## 🔍 Data Processing & EDA
- Imported dataset using Pandas  
- Handled missing values:
  - Replaced missing **review ratings** with the **median**  
- Performed Exploratory Data Analysis (EDA) to understand:
  - Customer distribution  
  - Purchase patterns  
  - Rating trends  

---

## 🧠 Feature Engineering
Created new features to enhance analysis:
- **Age Group** → Derived from age column  
- **Purchase Frequency (Days)** → Derived from frequency_of_purchases  ** → Based on frequency_of_purchases  

---

## 🗄️ Database Integration
- Connected Python with MySQL using **SQLAlchemy**  
- Created database and table  
- Loaded cleaned dataset into MySQL for further analysis  

---

## 📊 SQL Analysis
- Performed analytical queries to extract insights such as:
  - Customer segmentation  
  - Purchase trends  
  - Product performance  
These queries focus on solving real business questions such as revenue contribution, customer segmentation, discount effectiveness, and product performance.

📄 Queries are available in:  
👉 `analysis_queries.sql`

---

## 📈 Dashboard
- Built an interactive dashboard using **Power BI**
- Visualized:
  - Customer distribution, Revenue and Sales  
  - Purchase behavior  
  - Key performance trends  

📊 Dashboard file included in repository

---

## 🚀 Key Learnings
- End-to-end data analysis workflow (Python → SQL → Visualization)  
- Data cleaning and preprocessing techniques  
- Writing efficient SQL queries for business insights  
- Translating data into actionable insights  

---


## 💡 Key Insights
- Majority of revenue is driven by specific customer segments  
- Discounts influence purchasing behavior but not always higher spending  
- Customer segmentation helps identify loyal vs high-value users  
- Product-level analysis highlights opportunities for targeted promotions  


## 🤝 Conclusion
This project demonstrates how raw data can be transformed into meaningful insights that support better decision-making and business understanding.

---
