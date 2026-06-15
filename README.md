# 📊 Retail Sales Performance Dashboard

A **Power BI + Excel analytics project** that transforms raw retail transaction data into actionable business insights through interactive dashboards, data modeling, and DAX-driven KPIs.

---

## 🚀 Project Overview

This project focuses on analyzing **12 months of retail sales data (~15,000 records)** that was originally scattered across multiple Excel sheets with inconsistent formatting.

The goal was to transform messy, disconnected data into a unified dashboard that clearly shows revenue trends, product performance, and regional insights.

---

## ❗ Problem Statement

- Data spread across multiple Excel sheets with inconsistent structure  
- No unified view of revenue trends or KPIs  
- Difficulty identifying top products and weak regions  
- No self-serve reporting system for business users  

💡 Result: Decision-making was slow and not data-driven.

---

## 🧹 Data Cleaning & Preparation (Excel)

- Removed duplicate transaction IDs  
- Fixed inconsistent date formats  
- Handled missing product categories using product codes  
- Standardized column structure across all sheets  



---

## 🧠 Data Modeling (Power BI)

Built a **Star Schema**:

- Fact Table: Sales Transactions  
- Dimension Tables:
  - Products  
  - Customers  
  - Regions  
  - Date Table (`CALENDAR()` in DAX)

This improved performance and made analysis scalable.

---

## 📐 DAX Measures

Key KPIs created:

- 💰 Total Revenue  
- 📈 Month-over-Month Growth  
- 📊 Quarter-over-Quarter Growth  
- 🏷️ Category-wise Revenue Share  
- 📉 Year-over-Year Growth (`CALCULATE()` + `SAMEPERIODLASTYEAR()`)

---

## 📊 Dashboard Pages

### 1. Executive Summary
- Key KPIs: Revenue, Growth, Trends  
- High-level business snapshot  

### 2. Regional Analysis
- Map visuals for geographic insights  
- Regional performance comparison  
- Identification of weak vs strong regions  

### 3. Product Category Analysis
- Category performance breakdown  
- Trend analysis over time  
- Revenue contribution by segment  

---

## 🎛️ Interactivity

- Region slicer  
- Category slicer  
- Monthly filters  

👉 Enables self-service analytics for users.

---

## 🔍 Key Insights

- 📌 Electronics sales spike ~ more than 40% in Q4 (seasonal demand)  
- 📌 South region consistently underperforms vs North & West  
- 📌 Revenue is unevenly distributed across categories  

---

## 📚 Key Learnings

- Data cleaning is the most important step in analytics  
- Proper data modeling improves performance significantly  
- Dashboard design should focus on clarity, not complexity  
- Users understand insights within 30 seconds or they ignore it  

---

## 🛠️ Tools Used

- Power BI  
- Microsoft Excel  
- DAX  
- Data Modeling (Star Schema)

---

## 📌 Outcome

This project demonstrates how raw retail data can be transformed into a **decision-making tool** using analytics and visualization. It highlights both technical and business thinking skills.

## Executive Summary Dashboard



## Regional Analysis Dashboard



## Product Analysis Dashboard



---

## 👩‍💻 Author
**Sakshi Golambade** 

Data Analyst



---
