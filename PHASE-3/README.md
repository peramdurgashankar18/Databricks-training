# 🚀 PHASE-3 – Final ETL & Pipeline Practice

> **Transforming SQL knowledge into practical ETL pipelines using PySpark!** ⚡📊

This phase represents my hands-on practice with the complete ETL (**Extract, Transform, Load**) workflow using PySpark and SQL. I worked with structured datasets and implemented data ingestion, cleaning, transformation, aggregation, joins, and analytical reporting.

---

## 📂 Project Structure

```text
PHASE-3/
│
├── 📁 Outputs/
├── 🐍 Pyspark_phase-3.py
├── 🗄️ SQL_phase-3.sql
├── 📄 pyspark_sql_phase3_final_etl_pipeline_practice_pack.pdf
└── 📘 README.md
```

---

## 🎯 Objective

The main objective of this phase was to move beyond individual SQL queries and understand how complete ETL workflows are designed and implemented using PySpark.

### Key Objectives

* 📥 Read data from multiple file formats
* 🧹 Clean and validate datasets
* 🔄 Transform raw data into useful information
* 🤝 Combine datasets using joins
* 📊 Perform aggregations and analytical operations
* 📋 Generate reporting datasets
* ⚡ Understand the complete ETL workflow

---

## 🔄 ETL Workflow

```text
Extract
   ↓
Transform
   ↓
Load
```

### 📥 Extract

Loaded datasets from different file formats:

* CSV files
* JSON files
* Parquet files

### 🧹 Transform

Applied different data processing and transformation operations:

* Handle missing values
* Remove invalid records
* Convert data types
* Filter required data
* Join multiple datasets
* Perform aggregations
* Create analytical reports

### 📤 Load

Prepared transformed datasets for analysis and reporting:

* Display processed results
* Generate business reports
* Validate pipeline outputs
* Prepare final reporting datasets

---

## 📁 Files Overview

### 🐍 Pyspark_phase-3.py

Contains my PySpark implementation of the ETL workflow, including:

* SparkSession creation
* Reading CSV, JSON, and Parquet files
* Schema inspection
* NULL value handling
* Data cleaning
* Record filtering
* Data type conversion
* Aggregations
* DataFrame joins
* Window Functions
* Final reporting operations

---

### 🗄️ SQL_phase-3.sql

Contains SQL solutions for different data processing and business scenarios.

The SQL operations were also implemented using equivalent PySpark DataFrame transformations.

---

### 📄 PySpark SQL Phase-3 Practice Pack

Reference material used during this phase for:

* Learning ETL concepts
* Understanding Data Engineering workflows
* Guided practice exercises
* Business data scenarios
* Final pipeline challenges

---

### 📁 Outputs

Contains the results generated while executing the SQL and PySpark tasks:

* ✅ Execution screenshots
* ✅ Query results
* ✅ DataFrame outputs
* ✅ Pipeline results
* ✅ Validation results

---

## 📊 Datasets Used

Sample datasets used during the ETL practice:

* 👥 `customers.csv`
* 💰 `sales.csv`
* 📄 `sample.json`
* 📦 `sample.parquet`

These datasets helped me practice data ingestion, transformation, aggregation, and analytical reporting.

---

## 🧹 Data Cleaning Performed

Before performing analytical operations, I cleaned and validated the datasets.

* ✅ Removed records with missing `customer_id`
* ✅ Converted `total_amount` from String to Double
* ✅ Filtered invalid sales records
* ✅ Checked datasets for missing values
* ✅ Prepared clean datasets for further processing

---

## ✅ Hands-on Tasks Completed

| Status | Task                                   |
| ------ | -------------------------------------- |
| ✅      | Read CSV files                         |
| ✅      | Inspect DataFrames using `show()`      |
| ✅      | Inspect schemas using `printSchema()`  |
| ✅      | Identify missing values                |
| ✅      | Clean data using `dropna()`            |
| ✅      | Handle missing values using `fillna()` |
| ✅      | Filter invalid records                 |
| ✅      | Read JSON files                        |
| ✅      | Read Parquet files                     |
| ✅      | Perform DataFrame transformations      |

---

## 📈 Business Pipeline Exercises

| Status | Exercise                                            |
| ------ | --------------------------------------------------- |
| ✅      | Calculate daily sales                               |
| ✅      | Analyze city-wise revenue                           |
| ✅      | Identify repeat customers with more than two orders |
| ✅      | Find the highest-spending customer in each city     |
| ✅      | Generate a final customer reporting table           |

---

## 💻 SQL Concepts Practiced

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* `INNER JOIN`
* `LEFT JOIN`
* Aggregate Functions
* Window Functions
* `ROW_NUMBER()`
* `CONCAT()`

---

## ⚡ PySpark Concepts Practiced

* `SparkSession`
* DataFrames
* CSV Reader
* JSON Reader
* Parquet Reader
* `show()`
* `printSchema()`
* `dropna()`
* `fillna()`
* `filter()`
* `withColumn()`
* `cast()`
* `groupBy()`
* `agg()`
* `sum()`
* `avg()`
* `count()`
* `join()`
* `concat_ws()`
* `alias()`
* `orderBy()`
* Window Functions
* `row_number()`

---

## 🔄 SQL → PySpark Mapping

| SQL Operation | PySpark Operation           |
| ------------- | --------------------------- |
| SELECT        | `select()`                  |
| WHERE         | `filter()`                  |
| GROUP BY      | `groupBy()`                 |
| HAVING        | `filter()` after `agg()`    |
| ORDER BY      | `orderBy()`                 |
| JOIN          | `join()`                    |
| SUM()         | `sum()`                     |
| AVG()         | `avg()`                     |
| COUNT()       | `count()`                   |
| CONCAT()      | `concat_ws()`               |
| ROW_NUMBER()  | `row_number().over(Window)` |

---

## 🌟 Skills Developed

After completing this phase, I improved my ability to:

* ✨ Build structured ETL workflows using PySpark
* ✨ Read data from multiple file formats
* ✨ Clean and validate structured datasets
* ✨ Perform DataFrame transformations
* ✨ Apply joins and aggregations
* ✨ Use Window Functions for analytical problems
* ✨ Generate reporting datasets
* ✨ Translate SQL queries into PySpark transformations
* ✨ Apply Data Engineering concepts to practical datasets

---

## 🛠️ Technologies Used

* 🐍 Python
* ⚡ PySpark
* 🔥 Apache Spark
* 🗄️ SQL
* 💻 VS Code
* 🐙 Git & GitHub

---

## 🎯 Learning Outcome

Completing this phase strengthened my understanding of the ETL lifecycle and helped me understand how raw datasets can be cleaned, transformed, and converted into meaningful analytical results using PySpark.

This practice also improved my SQL-to-PySpark mapping skills and gave me hands-on experience with DataFrame transformations, joins, aggregations, and Window Functions.

---

## 👨‍💻 Author

**Shankar**

B.Tech Student | Java & DSA Learner | Exploring Data Engineering and Full Stack Development

⭐ *Learning, building, and improving through consistent hands-on practice.*
