# 🚀 PHASE-3 – Final ETL & Pipeline Practice

> **From SQL queries to building complete ETL pipelines with PySpark!** ⚡📊

This phase focuses on implementing an end-to-end ETL (**Extract, Transform, Load**) workflow using PySpark and SQL. The practice covers real-world data engineering tasks such as data ingestion, cleaning, filtering, transformation, aggregation, joins, and analytical reporting.

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

The main objective of this phase is to move from writing individual SQL queries to understanding and building structured ETL workflows using PySpark.

### Key Objectives

* 📥 Read data from multiple file formats
* 🧹 Clean and validate raw datasets
* 🔄 Transform data for analysis
* 🤝 Combine datasets using joins
* 📊 Perform aggregations and analytical operations
* 📋 Generate reporting datasets
* ⚡ Understand the complete ETL lifecycle

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

Data was loaded from multiple file formats:

* CSV
* JSON
* Parquet

### 🧹 Transform

The raw data was processed using different transformation techniques:

* Handling missing values
* Removing invalid records
* Data type conversion
* Filtering records
* Joining datasets
* Aggregating data
* Creating analytical reports

### 📤 Load

The transformed data was prepared for further analysis and reporting.

* Display processed results
* Generate business reports
* Validate transformed data
* Prepare reporting datasets

---

## 📁 Files Overview

### 🐍 Pyspark_phase-3.py

Contains the PySpark implementation of the ETL workflow.

Key operations include:

* Creating a SparkSession
* Reading CSV, JSON, and Parquet files
* Inspecting DataFrame schemas
* Handling NULL values
* Cleaning datasets
* Filtering records
* Performing aggregations
* Joining DataFrames
* Applying Window Functions
* Creating final reporting datasets

---

### 🗄️ SQL_phase-3.sql

Contains SQL queries written for different data processing and business analysis scenarios.

The SQL queries were also mapped to equivalent PySpark DataFrame transformations.

---

### 📄 PySpark SQL Phase-3 Practice Pack

The reference material contains:

* ETL learning objectives
* Data Engineering concepts
* Guided exercises
* Business analysis scenarios
* Final ETL challenges

---

### 📁 Outputs

The output folder contains execution results from the practice tasks.

* ✅ Execution screenshots
* ✅ SQL query results
* ✅ PySpark DataFrame outputs
* ✅ ETL pipeline results
* ✅ Data validation results

---

## 📊 Datasets Used

The ETL practice uses sample datasets including:

* 👥 `customers.csv`
* 💰 `sales.csv`
* 📄 `sample.json`
* 📦 `sample.parquet`

These datasets were used to practice data ingestion, transformation, aggregation, and reporting.

---

## 🧹 Data Cleaning Operations

Before performing analytical operations, the datasets were cleaned and validated.

* Removed records with missing `customer_id`
* Converted `total_amount` from String to Double
* Filtered invalid sales records
* Checked datasets for missing values
* Prepared clean datasets for analysis

---

## ✅ Hands-on Tasks Completed

| Status | Task                                   |
| ------ | -------------------------------------- |
| ✅      | Read CSV files                         |
| ✅      | Display DataFrames using `show()`      |
| ✅      | Inspect schemas using `printSchema()`  |
| ✅      | Identify missing values                |
| ✅      | Clean data using `dropna()`            |
| ✅      | Handle missing values using `fillna()` |
| ✅      | Filter invalid records                 |
| ✅      | Read JSON files                        |
| ✅      | Read Parquet files                     |
| ✅      | Perform DataFrame transformations      |

---

## 📈 Business Analysis Exercises

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

* Build structured ETL workflows using PySpark
* Read data from multiple file formats
* Clean and validate structured datasets
* Perform DataFrame transformations
* Apply joins and aggregations
* Use Window Functions for analytical problems
* Create reporting datasets
* Translate SQL queries into PySpark transformations
* Understand practical Data Engineering workflows

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

This phase strengthened my understanding of the complete ETL lifecycle and helped me practice transforming raw data into meaningful analytical results using PySpark.

I also improved my understanding of SQL-to-PySpark mapping, DataFrame transformations, data cleaning, joins, aggregations, and Window Functions used in practical Data Engineering workflows.

---

## 👨‍💻 Author

**Shankar**

B.Tech Student | Java & DSA Learner | Exploring Data Engineering and Full Stack Development

⭐ *Learning, building, and improving through consistent hands-on practice.*
