
# 🧼 Data Cleaning on Layoffs Dataset (SQL)

## 📄 Description
This project focuses on **cleaning and preparing a real-world dataset** of global tech layoffs (sourced from [Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022)) using **SQL**.

The goal was to ensure data quality and consistency for downstream analysis by performing the following tasks.

---

## ✅ Key Objectives
- Remove duplicate rows using `ROW_NUMBER()` and CTEs
- Handle missing and blank values (e.g., nullifying and filling `industry` column)
- Standardize inconsistent data (e.g., fixing variations in `industry`, `country`, and date formats)
- Convert and clean up the `date` field using `STR_TO_DATE()`
- Remove unusable rows with completely null values
- Finalize a clean, analysis-ready staging table

---

## 🛠️ Skills & Tools Used
- MySQL / SQL Server
- Window functions (`ROW_NUMBER()`)
- Data cleaning best practices
- Joins, updates, deletes, data type conversion

---

## 📁 Dataset Source
[Kaggle – Layoffs Dataset (2022)](https://www.kaggle.com/datasets/swaptr/layoffs-2022)
