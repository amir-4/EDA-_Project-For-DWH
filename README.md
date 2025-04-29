# 🛒 Advanced Retail Analytics Using SQL – Data Warehouse Insights

Welcome to the **Retail Analytics SQL Project**, where we apply advanced SQL techniques on a **star schema data warehouse** to extract meaningful insights across customer behavior, product performance, and sales trends. This project demonstrates how to transform raw data into **actionable business intelligence** using SQL only.

---

## 🚀 Project Overview

This project aims to:
- Analyze a **retail data warehouse** structured with fact and dimension tables.
- Execute advanced **SQL queries** to derive critical business KPIs.
- Segment customers and identify revenue patterns and churn risks.
- Create a **Gold View layer** for seamless integration with BI tools like Power BI or Tableau.

---

## 🧱 Data Model (Star Schema)
                         +------------------+
                         |   dim_customers   |
                         +------------------+
                                |
                                |
+------------+        +---------+--------+       +------------+
| dim_dates  |<------>|   fact_sales    |<----->| dim_products |
+------------+        +------------------+       +------------+
                                |
                         +------------------+
                         |  dim_categories   |
                         +------------------+

---

## 📊 Key Analyses Performed

### 🧭 Schema Discovery
- Used `INFORMATION_SCHEMA` to dynamically extract table and column metadata.
- Validated schema completeness and data availability.

### 📈 Descriptive & Diagnostic KPIs
- Aggregated metrics: revenue, order count, quantity sold, ASP.
- Time-trended metrics using `DATE_TRUNC()` for monthly breakdowns.
- Demographic splits by gender, age group, and geography.

### 🎯 Customer Segmentation
- Classified customers into age groups using `CASE` statements.
- Behavior-based segmentation: **New**, **Regular**, and **VIP**.
- Identified acquisition and retention windows.

### 🏆 Ranking & Performance Insights
- Used `ROW_NUMBER()` and `RANK()` to detect top revenue contributors.
- Highlighted underperforming and overperforming SKUs.
- Detected potential churn among inactive customer groups.

### 🧠 Gold Layer – Reporting View
- Created `gold.report_customers` containing:
  - Average Order Value (AOV)
  - Lifetime value estimates
  - First & last purchase timestamps
  - Purchase frequency metrics

---

## 🛠️ Tools & Technologies

| Tool / Tech     | Purpose                                 |
|-----------------|------------------------------------------|
| SQL (BigQuery, PostgreSQL, MySQL) | Data querying and transformation |
| Data Warehouse  | Star schema modeling and storage         |
| BI Tools (optional) | Dashboard creation using semantic layer |
| GitHub          | Version control and collaboration        |

---

## 📁 Repository Structure


---

## 📌 What You’ll Learn

- ✅ How to work with a dimensional model using SQL
- ✅ Writing efficient and scalable analytical queries
- ✅ Segmenting customers based on behavior and sales
- ✅ Creating a reporting-ready view for BI integration

---

## 👨‍💻 Author
**Amir Mansour Eid Mohammed**  
Data Analyst | SQL Expert | BI Enthusiast  
🔗 [LinkedIn](www.linkedin.com/in/amir-mansour-808530263)  
📧 amiir.mansourr@gmail.com

---

## 📢 License

This project is licensed under the MIT License – you are free to use, modify, and distribute.

---

> ⭐ *If you found this project helpful, feel free to star the repo and connect with me on LinkedIn!*

