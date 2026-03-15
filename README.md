# 🚀 FMCG Sales Analytics Pipeline (Databricks)

An **end-to-end Data Engineering project** built using **Databricks, Apache Spark (PySpark), Delta Lake, and SQL** to process FMCG sales data and generate business insights.

The pipeline follows the **Medallion Architecture (Bronze → Silver → Gold)** to transform raw data into analytics-ready datasets and power an interactive dashboard.

---

# 🏗️ Architecture

```
Raw Data
   │
   ▼
Bronze Layer (Data Ingestion)
   │
   ▼
Silver Layer (Data Cleaning & Transformation)
   │
   ▼
Gold Layer (Aggregated Analytics Tables)
   │
   ▼
BI Dashboard (Business Insights)
```

---

# ⚙️ Tech Stack

* **Databricks**
* **Apache Spark (PySpark)**
* **Delta Lake**
* **SQL**
* **Databricks Dashboards**

---

# 📂 Project Structure

```
fmcg-sales-analytics-databricks
│
├── ingestion
│   ├── customer_data_processing.ipynb
│   ├── products_data_processing.ipynb
│   └── pricing_data_processing.ipynb
│
├── pipeline
│   ├── setup_catalogs.ipynb
│   ├── utilities.ipynb
│   └── dim_date_table_creation.ipynb
│
├── fact_tables
│   ├── full_load_fact.ipynb
│   └── incremental_load_fact.ipynb
│
├── dashboard
│   └── sales_insights_dashboard.png
│
└── README.md
```

---

# 📊 Dashboard Features

### KPI Metrics

* Total Revenue
* Total Quantity Sold
* Total Unique Customers
* Average Selling Price

### Business Insights

* Monthly Revenue Trend
* Top 10 Products by Revenue
* Revenue by Sales Channel
* Customer Revenue Analysis
* Top Product Variants by Revenue
* Product Price vs Quantity Analysis

---



# 🔥 Skills Demonstrated

✔ Data Engineering Pipelines
✔ Medallion Architecture
✔ Delta Lake Tables
✔ Incremental Data Processing
✔ Spark & SQL Analytics
✔ Dashboard Design

---

# 👨‍💻 Author

**Aryaman Bhardwaj**
BSc (Research) – Data Science & Analytics
Aspiring Data Engineer

---
