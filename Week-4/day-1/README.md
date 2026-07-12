# Week 4 - Day 1: PySpark DataFrame Transformations - Part 1

## Overview

On Week 4 Day 1, I practiced fundamental PySpark DataFrame transformations used for data processing and data engineering tasks.

Through hands-on exercises, I worked with DataFrame creation, selection, filtering, column transformations, data cleaning, sorting, and aggregation.

## Objective

The main objective of this practice was to improve my understanding of PySpark DataFrame transformations and apply different DataFrame operations to employee datasets.

## Files Included

| File                                          | Description                                            |
| --------------------------------------------- | ------------------------------------------------------ |
| `Pyspark_DataFrame_Practice_starter_file.txt` | Contains the starter dataset and basic PySpark code.   |
| `PySpark_DataFrame_Practice_Ass-1.txt`        | Contains exercises based on DataFrame transformations. |
| `PySpark_DataFrame_Practice_Ass-2.txt`        | Contains additional DataFrame practice exercises.      |

## Concepts Practiced

### DataFrame Creation

* Created an employee DataFrame using PySpark.
* Worked with sample employee data.
* Defined columns and explored the DataFrame.
* Displayed data using DataFrame operations.

### Data Selection

* Selected specific columns using `select()`.
* Retrieved required employee information.
* Displayed selected columns for analysis.

### Data Filtering

* Used `filter()` and `where()` to retrieve specific records.
* Applied conditions based on salary, department, age, city, and gender.
* Combined multiple filtering conditions using logical operators.

### Column Transformations

* Added new columns using `withColumn()`.
* Renamed columns using `withColumnRenamed()`.
* Created conditional columns using `when()`.
* Used `alias()` to provide meaningful column names.

### Data Cleaning

* Removed unnecessary columns using `drop()`.
* Retrieved unique records using `distinct()`.
* Removed duplicate records using `dropDuplicates()`.

### Sorting and Ordering

* Sorted DataFrame records in ascending order.
* Sorted records in descending order.
* Applied sorting using multiple columns.
* Organized employee data for easier analysis.

### Aggregations

* Grouped DataFrame records using `groupBy()`.
* Calculated total values using `sum()`.
* Calculated average values using `avg()`.
* Identified minimum and maximum values.
* Counted records using `count()`.
* Used `agg()` to perform multiple aggregate operations.

## PySpark Functions Used

The following PySpark functions and DataFrame operations were practiced:

* `createDataFrame()`
* `select()`
* `filter()`
* `where()`
* `withColumn()`
* `withColumnRenamed()`
* `drop()`
* `distinct()`
* `dropDuplicates()`
* `orderBy()`
* `sort()`
* `groupBy()`
* `agg()`
* `sum()`
* `avg()`
* `min()`
* `max()`
* `count()`
* `when()`
* `alias()`

## Important Concepts Learned

* Creating and exploring PySpark DataFrames.
* Selecting required DataFrame columns.
* Filtering records using different conditions.
* Adding and renaming DataFrame columns.
* Creating conditional columns.
* Cleaning duplicate and unnecessary data.
* Sorting records using single and multiple columns.
* Grouping data for analysis.
* Performing aggregate calculations.
* Combining multiple DataFrame transformations.

## Technologies Used

* Databricks
* PySpark
* Apache Spark
* PySpark DataFrame API

## Learning Outcome

Through this practice, I gained hands-on experience with PySpark DataFrame transformations and improved my understanding of data selection, filtering, cleaning, sorting, grouping, and aggregation.

This practice also helped me understand how multiple DataFrame operations can be combined to process structured data.

## Week 4 - Day 1 Progress

Completed Week 4 Day 1 of my PySpark learning journey by practicing core DataFrame transformations and applying them to data processing exercises.
