# 🧹 SQL Layoffs Data Analysis

This project demonstrates the process of cleaning the **World Layoffs** dataset using **MySQL**. The objective is to transform raw data into a clean, consistent, and analysis-ready dataset by applying various SQL data cleaning techniques.

---

## 📌 Project Overview

Real-world datasets often contain duplicate records, missing values, inconsistent formatting, and incorrect data types. In this project, SQL was used to clean the World Layoffs dataset and prepare it for further analysis.

---

## 📂 Dataset

- **Dataset:** World Layoffs
- **Source:** Kaggle
- **Database:** MySQL
- **Tool Used:** MySQL Workbench

---

## 🎯 Objectives

- Create a staging table to preserve the original data.
- Identify and remove duplicate records.
- Standardize inconsistent values.
- Convert date values into the proper format.
- Handle missing and blank values.
- Prepare a clean dataset for Exploratory Data Analysis (EDA).

---

## 🛠 Technologies Used

- MySQL
- MySQL Workbench
- Git & GitHub

---

## 🧹 Data Cleaning Steps

The following data cleaning operations were performed:

- Created a staging table.
- Copied raw data into the staging table.
- Identified duplicate records using `ROW_NUMBER()`.
- Removed duplicate rows.
- Standardized company names using `TRIM()`.
- Standardized country names.
- Converted the `date` column into the `DATE` datatype.
- Replaced blank values with `NULL`.
- Filled missing `industry` values using a self-join.
- Removed unnecessary records with insufficient data.
- Dropped helper columns used during cleaning.

---

## 💡 SQL Concepts Used

- CREATE TABLE
- INSERT INTO
- UPDATE
- DELETE
- ALTER TABLE
- CTE (Common Table Expression)
- ROW_NUMBER()
- PARTITION BY
- JOIN
- CASE
- TRIM()
- STR_TO_DATE()
- IS NULL
- Window Functions

---

## 📁 Repository Structure

```
sql-layoffs-data-analysis/
│
├── dataset/
│   └── layoffs.csv
│
├── sql/
│   └── 01_data_cleaning.sql
│
├── screenshots/
│   ├── 01_original_dataset.png
│   ├── 02_duplicate_rows.png
│   ├── 03_standardize_data.png
│   └── 04_final_cleaned_dataset.png
│
├── README.md
└── LICENSE
```
---

## 🚀 Future Improvements

- Perform Exploratory Data Analysis (EDA)
- Generate business insights using SQL
- Add advanced SQL queries for trend analysis

---

## 📚 Key Learning Outcomes

Through this project, I strengthened my understanding of:

- SQL Data Cleaning
- Window Functions
- Common Table Expressions (CTEs)
- Data Standardization
- Handling Missing Values
- SQL Best Practices
- Preparing data for analysis

---

## 👩‍💻 Author

**Sneha Severiya**

- GitHub: https://github.com/snehaseveriya23
- LinkedIn: https://www.linkedin.com/in/sneha-severiya-205203376

---

⭐ If you found this project useful, consider giving it a star!
