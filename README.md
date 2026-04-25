# Customer Shopping Behavior Analysis

End-to-end data analytics project analyzing 3,900 customer transactions to extract insights on purchasing behavior, customer segmentation, and revenue trends using Python, SQL, and Power BI.

---

## 📌 Overview

This project focuses on understanding customer shopping patterns and identifying actionable business insights. The workflow includes data preprocessing in Python, analytical querying using SQL, and interactive dashboard creation in Power BI.

---

## 📂 Dataset

* Source: Customer Shopping Behavior Dataset
* Size: 3,900 transactions
* Features: 18 columns (demographics, purchases, behavior)
* Missing values handled in `review_rating` using median imputation

---

## 🛠 Tools & Technologies

* Python (Pandas, NumPy)
* SQL (PostgreSQL)
* Power BI
* Jupyter Notebook

---

## ⚙️ Project Workflow

### 1. Data Loading & Exploration

* Used Pandas to load dataset
* Performed `info()` and `describe()`

### 2. Data Cleaning

* Handled missing values
* Converted column names to snake_case

### 3. Feature Engineering

* Created `age_group`
* Derived `purchase_frequency_days`

### 4. SQL Analysis

* Exported data to PostgreSQL
* Analyzed revenue, segmentation, and product trends

### 5. Dashboard Development

* Built interactive Power BI dashboard with filters

---

## 📊 Dashboard Highlights

* Total Customers: 3.9K
* Avg Purchase Amount: $59.76
* Avg Review Rating: 3.75

---

## 🔍 Key Insights

* Male customers generate higher revenue
* Majority customers are loyal
* Large non-subscriber base → growth opportunity
* Young adults contribute most revenue

---

## 📈 Business Recommendations

* Improve subscription conversion
* Build loyalty programs
* Optimize discount strategies

---

## ▶️ How to Run

### Clone Repository

git clone https://github.com/codewithnihar2027/customer_behavior_analysis.git
cd customer_behavior_analysis

### Run Notebook

Open: Customer_Shopping_Behaviour_Analysis.ipynb
Run all cells

### Run SQL

Execute: customer_shopping_behavior_analysis.sql

### Open Dashboard

Open: Customer_Behavior.pbix

---

## 📎 Project Structure

Customer_Behavior.pbix
Customer_Shopping_Behaviour_Analysis.ipynb
customer_shopping_behavior.csv
customer_shopping_behavior_analysis.sql
README.md
LICENSE

---

## 👤 Author

Nihar Suman
GitHub: https://github.com/codewithnihar2027
