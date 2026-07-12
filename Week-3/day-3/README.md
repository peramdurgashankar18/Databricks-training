# Day 3: PySpark FILTER and WHERE Operations

## Overview

On Day 3, I practiced filtering data in PySpark DataFrames using `filter()` and `where()`.

These operations helped me understand how to retrieve specific records from a DataFrame based on different conditions.

## FILTER and WHERE Operations

The following filtering operations were practiced:

1. Filtered employees whose salary is greater than `70000`.
2. Filtered employees from Hyderabad.
3. Filtered employees whose age is less than `25`.
4. Filtered employees from the IT department.
5. Filtered employees whose designation is Developer.
6. Filtered employees whose salary is between `50000` and `80000`.
7. Filtered employees from Bangalore.
8. Filtered employees who joined after `2022-01-01`.
9. Filtered employees whose age is greater than `30`.
10. Filtered employees whose salary is less than `50000`.
11. Filtered employees from Chennai with a salary greater than `60000`.
12. Filtered employees from Mumbai or Pune.
13. Filtered employees whose names start with `S`.
14. Filtered employees whose names end with `a`.
15. Filtered employees from the HR department.
16. Filtered employees whose designation contains `Engineer`.
17. Filtered employees whose city is not Hyderabad.
18. Filtered employees aged between `25` and `30`.
19. Filtered employees whose salary is greater than `90000`.
20. Filtered employees from the Support department.

## Functions and Operators Used

### filter()

The `filter()` function is used to select rows that satisfy a specified condition.

**Example:**
`df.filter(col("salary") > 70000).show()`

### where()

The `where()` function is another way to filter DataFrame records.

**Example:**
`df.where(col("city") == "Hyderabad").show()`

### AND Condition (&)

The `&` operator combines multiple conditions where all conditions must be true.

**Example:**
`df.filter((col("city") == "Chennai") & (col("salary") > 60000)).show()`

### OR Condition (|)

The `|` operator combines conditions where at least one condition must be true.

**Example:**
`df.filter((col("city") == "Mumbai") | (col("city") == "Pune")).show()`

### between()

The `between()` function checks whether a value is within a specified range.

**Example:**
`df.filter(col("salary").between(50000, 80000)).show()`

### startswith()

The `startswith()` function checks whether a string begins with specified characters.

**Example:**
`df.filter(col("emp_name").startswith("S")).show()`

### endswith()

The `endswith()` function checks whether a string ends with specified characters.

**Example:**
`df.filter(col("emp_name").endswith("a")).show()`

### contains()

The `contains()` function checks whether a column contains specified text.

**Example:**
`df.filter(col("designation").contains("Engineer")).show()`

## Technologies Used

* Databricks
* PySpark
* Spark DataFrames
* PySpark DataFrame API

## Important Concepts Learned

* Filtering DataFrame records.
* Using `filter()` and `where()`.
* Applying comparison conditions.
* Combining multiple conditions using AND and OR operators.
* Filtering values within a range.
* Filtering text using string conditions.
* Working with date-based filtering.
* Applying multiple conditions to DataFrame columns.

## Day 3 Progress

Completed Day 3 of my PySpark learning journey by practicing FILTER and WHERE operations using different conditions in Databricks.
