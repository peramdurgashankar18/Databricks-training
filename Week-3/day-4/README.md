# Day 4: PySpark withColumnRenamed() Operations

## Overview

On Day 4, I practiced renaming columns in PySpark DataFrames using the `withColumnRenamed()` function.

This helped me understand how to modify DataFrame column names and improve the readability of a DataFrame schema.

## withColumnRenamed() Operations

The following column renaming operations were practiced:

1. Renamed `emp_name` to `employee_name`.
2. Renamed `department` to `dept`.
3. Renamed `joining_date` to `doj`.
4. Renamed `salary` to `monthly_salary`.
5. Renamed `designation` to `job_role`.
6. Renamed `city` to `work_location`.
7. Renamed `age` to `employee_age`.
8. Renamed multiple columns one by one.
9. Renamed `emp_id` to `employee_id`.
10. Renamed `department` to `business_unit`.

## Function Used

### withColumnRenamed()

The `withColumnRenamed()` function is used to rename an existing column in a PySpark DataFrame.

**Syntax:**
`df.withColumnRenamed("old_column_name", "new_column_name")`

**Example:**
`df.withColumnRenamed("emp_name", "employee_name").show()`

## Renaming Multiple Columns

Multiple columns can be renamed by chaining the `withColumnRenamed()` function.

**Example:**

```python
df.withColumnRenamed("emp_id", "employee_id") \
  .withColumnRenamed("emp_name", "employee_name") \
  .withColumnRenamed("salary", "monthly_salary") \
  .show()
```

Each `withColumnRenamed()` operation returns a new DataFrame with the updated column name.

## Technologies Used

* Databricks
* PySpark
* Spark DataFrames
* PySpark DataFrame API

## Important Concepts Learned

* Renaming DataFrame columns.
* Improving column name readability.
* Modifying DataFrame schemas.
* Renaming multiple columns.
* Chaining DataFrame operations.
* Understanding DataFrame immutability.

## Day 4 Progress

Completed Day 4 of my PySpark learning journey by practicing column renaming operations using `withColumnRenamed()` in Databricks.
