# Day 2: PySpark DataFrame SELECT and ALIAS Operations

## Overview

On Day 2, I practiced PySpark DataFrame operations using `select()` and `alias()` in Databricks.

These operations helped me understand how to select specific columns, filter DataFrame records, and display columns using meaningful names.

## SELECT Operations

The following SELECT operations were practiced:

1. Selected `emp_name` and `salary`.
2. Selected `emp_id`, `emp_name`, and `department`.
3. Selected `city`, `designation`, and `salary`.
4. Filtered employees from the IT department and selected specific columns.
5. Selected `emp_name`, `salary`, and `joining_date`.
6. Displayed the complete DataFrame.
7. Selected only the `salary` column.
8. Filtered employees from Hyderabad and selected `emp_name` and `city`.
9. Selected `designation` and `department`.
10. Displayed all columns except `joining_date`.

## ALIAS Operations

The `alias()` function was used to display DataFrame columns with different names.

The following alias operations were practiced:

1. `emp_name` as `employee_name`
2. `salary` as `monthly_salary`
3. `department` as `dept`
4. `joining_date` as `doj`
5. `emp_name` as `name` and `city` as `location`
6. `designation` as `job_role`
7. `age` as `employee_age`
8. Multiple columns using different aliases
9. `city` as `work_location`
10. `salary` as `emp_salary` and `department` as `emp_dept`

## Functions Used

### select()

The `select()` function is used to select one or more columns from a PySpark DataFrame.

**Example:**

`df.select("emp_name", "salary").show()`

### alias()

The `alias()` function provides a temporary name for a DataFrame column.

**Example:**

`col("emp_name").alias("employee_name")`

### filter()

The `filter()` function is used to select rows that satisfy a specified condition.

**Example:**

`df.filter(col("department") == "IT")`

### drop()

The `drop()` function removes a specified column from the displayed DataFrame.

**Example:**

`df.drop("joining_date").show()`

## Technologies Used

* Databricks
* PySpark
* PySpark DataFrame API

## Important Concepts Learned

* Selecting specific DataFrame columns.
* Working with multiple columns.
* Renaming displayed columns using `alias()`.
* Filtering DataFrame records.
* Removing columns using `drop()`.
* Using PySpark column expressions.
* Method chaining in PySpark.

## Day 2 Progress

Completed Day 2 of my PySpark learning journey by practicing DataFrame SELECT and ALIAS operations in Databricks.
