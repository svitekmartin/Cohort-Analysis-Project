# 🧠 Customer Retention Cohort Analysis

## 📘 Overview

This project explored a **modern marketing analytics pipeline** with a focus on customer retention and cohort analysis. The workflow integrated data across cloud tools to uncover insights into how long it takes customers to make repeat purchases.

---

### 🎯 Objective

The goal was to build an end-to-end data analytics solution by:

- 🔄 **Ingesting** e-commerce sales data from a **GCP Cloud SQL** database using **Fivetran**
- 🔧 **Transforming** and modeling the data in **Databricks**, leveraging **Delta Lake**
- 📊 **Visualizing** cohort trends (e.g. *time to second purchase*) in **Databricks Dashboards**

By the end of this project, the full journey through the **modern data stack** — from ingestion to transformation and visualization — was implemented to answer real marketing questions.

---

## 🧑‍💼 Use Case Background

Since customer acquisition is expensive, businesses need to understand whether new customers return for a second purchase. This project addressed that by applying **cohort analysis**, where cohorts were defined by customers’ **first purchase month**.

> **Core Question:**  
> *How long does it take customers to make their second purchase, and how does that vary between cohorts?*

---

## 🔁 Data Workflow

1. **Data Ingestion (Fivetran)**
   - The pipeline connected to a **Google Cloud SQL (BigQuery)** database containing raw sales data.
   - Tables and schema were automatically replicated into **Delta Lake** on **Databricks**.

2. **Data Transformation (Databricks SQL)**
   - Raw data was transformed into a model optimized for cohort analysis.
   - SQL queries (including **CTEs** and **subqueries**) computed the **first and second purchase dates** for each customer.

3. **Visualization (Databricks Dashboards)**
   - The transformed data was visualized to highlight:
     - Time-to-second-purchase by cohort
     - Retention and repeat purchase patterns over time

---

## 📦 Final Deliverables

The final project deliverables included:

- 📈 **Dashboards** visualizing cohort behavior and retention trends
- 📁 **SQL scripts** used for data modeling, transformation, and cohort computation

All project artifacts were organized and prepared for live presentation.

---

## 🛠️ Teck Stack

- **Fivetran** – For automated data ingestion
- **Google Cloud SQL (BigQuery)** – Source database
- **Databricks + Delta Lake** – Storage, modeling, and transformation
- **Databricks SQL Dashboards** – Visualization and reporting

---

