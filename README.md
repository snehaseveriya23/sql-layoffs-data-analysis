# SQL Layoffs Data Analysis

## Project Overview

This project focuses on cleaning the World Layoffs dataset using SQL. The goal is to transform raw data into a clean and consistent dataset that is ready for analysis.

## Dataset

- Dataset: World Layoffs
- Source: Kaggle

## Tools Used

- MySQL
- MySQL Workbench
- GitHub

## Data Cleaning Steps

- Created a staging table
- Removed duplicate records
- Standardized text values
- Converted date format
- Handled NULL and blank values
- Filled missing industry values
- Removed unnecessary records
- Dropped helper columns

## SQL Concepts Used

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

## Project Structure

```
sql-layoffs-data-analysis/
│
├── dataset/
│   └── layoffs.csv
│
├── sql/
│   └── 01_Data_Cleaning.sql
│
├── screenshots/
│
├── README.md
└── LICENSE
```

## Future Work

- Perform Exploratory Data Analysis (EDA)
- Generate business insights
