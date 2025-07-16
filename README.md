# 🧹 Olist Data Cleaning & Transformation

Transforming the raw Olist e‑commerce dataset into clean, analysis-ready tables using Python, PySpark, and Databricks.

---

## 📁 Overview

This project focuses on implementing comprehensive **data cleaning and transformation** steps on the Olist dataset—a real‑world Brazilian e‑commerce database. The notebook (📘 `olyst data cleaning.ipynb`) walks through:

- ✅ Data ingestion  
- ✅ Handling missing values, duplicates, and outliers  
- ✅ Data type conversions and standardizations  
- ✅ Joining multiple tables (orders, customers, payments, reviews, etc.)  
- ✅ Generating clean, usable tables for downstream analytics  

---

## 🔍 What You'll See

1. **Data Profiling**:  
   - Exploratory checks for nulls and anomalies  
2. **Cleaning Techniques**:  
   - Dropping duplicates  
   - Imputing or removing nulls  
   - Fixing inconsistent formats (dates, currency)  
3. **Transformation Logic**:  
   - Data type casting (e.g., timestamp parsing)  
   - Creating derived columns (e.g., delivery time, order intervals)  
   - Joining across tables for enriched datasets  
4. **Output**:  
   - Clean tables ready for loading into a data warehouse or analytics tool

---

## 🛠️ Tools & Tech

- **🐍 Python** + **Pandas** & **PySpark** (Databricks—leveraging its scalability)
- **Databricks notebook** environment (`olyst data cleaning.ipynb`)
- Recommended for:
  - Large-scale dataset transformations  
  - Reusable ETL pipelines in Databricks  

---

## 🚀 How to Run

1. Clone this repo and open `olyst data cleaning.ipynb` in Databricks.
2. Install dependencies:  
   ```bash
   pip install pyspark pandas
