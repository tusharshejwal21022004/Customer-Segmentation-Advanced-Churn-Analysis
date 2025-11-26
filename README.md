# 📊 Customer Segmentation Visualization & Advanced Analysis

An end-to-end **Business Analytics and Data Science Project** designed to analyze customer churn in a telecommunications company and build predictive insights to identify at-risk customers.

---

## 🚀 Project Overview
The project aims to analyze customer churn in a telecommunications company and develop predictive models to identify at-risk customers.  
The ultimate goal is to provide **actionable insights and recommendations** to reduce churn and improve customer retention.

This project uses **Python (Pandas, NumPy, Matplotlib)** to perform complete data analysis — from data cleaning to visualization and advanced churn insights.

---

## 💼 Business Objective
1. Understand customer behavior patterns leading to churn  
2. Segment customers by tenure and contract type  
3. Identify factors influencing churn (demographics, billing, contract duration)  
4. Provide insights for customer retention strategies  

---

## 🧩 Dataset
**Name:** Telco Customer Churn Dataset  
**Source:** Kaggle  
**Rows:** ~7,043  
**Columns:** 21  

### Key Features:
- `CustomerID` – Unique customer identifier  
- `Gender`, `SeniorCitizen`, `Partner`, `Dependents`  
- `Tenure` – Number of months customer stayed  
- `MonthlyCharges`, `TotalCharges` – Billing details  
- `Contract`, `PaymentMethod`, `InternetService`, `Churn`

---

## ⚙️ Tools & Libraries Used
| Tool | Purpose |
|------|----------|
| Python | Core programming |
| Pandas | Data cleaning & analysis |
| NumPy | Numerical operations |
| Matplotlib | Visualization |
| Jupyter Notebook | Interactive environment |

---

## 🧠 Project Tasks

### **Task 1: Understanding the Dataset**
- Loaded and explored data  
- Checked shape, datatypes, missing values  

### **Task 2: Data Cleaning**
- Standardized column names  
- Converted `TotalCharges` to numeric  
- Filled missing values with median/mode  
- Removed duplicates  
- Created `tenure_bucket` column (`0–12`, `13–36`, `37+`)

### **Task 3: Exploratory Data Analysis (EDA)**
- Generated summary statistics  
- Visualized key numeric distributions  
- Analyzed churn proportions  

### **Task 4: Customer Segmentation Visualization**
- **Donut Chart:** Distribution of customers by tenure  
- **Bar Chart:** Average monthly charges by tenure segment  


---

## 📈 Key Insights
- Customers with **month-to-month contracts** churn the most  
- **Senior citizens** and **fiber optic users** are more likely to leave  
- **Higher monthly charges** → greater churn risk  
- **Longer tenure customers** show strong loyalty (low churn)  

---


