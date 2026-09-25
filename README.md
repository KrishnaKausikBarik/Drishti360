# Drishti360: End-to-End Customer Shopping Intelligence Platform

**Drishti360** represents a complete, industry-standard, end-to-end data analytics workflow designed to provide a 360-degree vision into modern consumer behavior. The project mirrors the real-world responsibilities of professional data analysts, spanning data preparation, feature engineering, relational database modeling, business logic querying, and executive reporting.

---

## 📌 Project Overview

The objective of **Drishti360** is to transform raw retail transaction data into actionable business intelligence across four structured phases:

* **Data Engineering & EDA (Python):** Clean, preprocess, and enrich the raw shopping behavior dataset. Missing review ratings are imputed with category medians, redundant indicators are eliminated, and analytical dimensions (`age_group`, `purchase_frequency_days`) are engineered.
* **Database Architecture (SQL):** Establish programmatic pipelines to ingest structured data into enterprise databases (PostgreSQL, MySQL, or MS SQL Server) and execute SQL queries to analyze customer retention, segment spending, and discount sensitivity.
* **Business Intelligence (Power BI):** Deploy the **Drishti360 Dashboard**, connecting directly to the SQL layer to visualize multidimensional consumer patterns, sales metrics, and demographic trends.
* **Executive Presentation:** Translate findings into an executive-ready project report and presentation deck generated via Gamma AI for stakeholder communication.

---

## 🏗️ Repository Architecture

```text
Drishti360/
├── data/
│   └── customer_shopping_behavior.csv
├── notebooks/
│   └── Customer_Shopping_Behavior_Analysis.ipynb
├── sql/
│   └── customer_behavior_sql_queries.sql
├── dashboard/
│   └── Drishti360_dashboard.pbix
├── presentation/
│   └── Drishti360_executive_deck.pdf
├── README.md
└── LICENSE
