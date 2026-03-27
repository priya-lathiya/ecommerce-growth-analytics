# ecommerce-growth-analytics
End-to-end e-commerce data analytics project featuring RFM segmentation, churn detection &amp; KPI tracking built on real Brazilian e-commerce data using PostgreSQL, Python &amp; Power BI.

---

## 📌 Project Overview

This is an end-to-end data analytics portfolio project built on real-world Brazilian
e-commerce data. The goal is to analyze customer behavior, track key business KPIs,
segment customers using RFM analysis, and detect potential churn — all presented
through a professional business dashboard.

This project demonstrates a complete data analyst workflow:

**Data Collection → Data Cleaning → Exploratory Analysis → Customer Segmentation → Dashboard & Insights**

---

## 🎯 Project Objectives

- Track key business KPIs: revenue, order volume, and average order value
- Identify top performing product categories and regions
- Segment customers using RFM (Recency, Frequency, Monetary) analysis
- Detect at-risk and churned customers
- Deliver actionable business insights through an interactive dashboard

---

## 🗂️ Dataset

**Source:** [Olist Brazilian E-Commerce Dataset — Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

**Description:** Real e-commerce transaction data from Olist, the largest department
store in Brazilian marketplaces. The dataset contains 100,000+ orders placed between
2016 and 2018 across 9 relational tables.

### Dataset Overview

| Property | Value |
|---|---|
| Total Orders | 99,441 |
| Total Customers | 99,441 |
| Total Products | 32,951 |
| Total Sellers | 3,095 |
| Total Revenue | R$ 16,008,872.12 |
| Date Range | September 2016 — October 2018 |
| Total Tables | 9 CSV files |


---

## 📁 Project Structure

```
ecommerce-growth-analytics/
│
├── data/
│   └── raw/                        # Original CSV files from Kaggle
│
├── sql/
│   ├── 01_create_tables.sql        # Table creation scripts
│   ├── 02_data_cleaning.sql        # All data cleaning queries
│   ├── 03_eda_queries.sql          # Exploratory analysis queries
│   └── 04_kpi_queries.sql          # KPI calculation queries
│
├── python/
│   ├── rfm_segmentation.py         # RFM analysis script
│   └── churn_detection.py          # Churn detection script
│
├── dashboard/
│   └── ecommerce_dashboard         # Power BI / Tableau file
│
├── reports/
│   └── Step3_Data_Cleaning_Report.txt
│
└── README.md
```

---

