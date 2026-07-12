# Week 4 - Day 4: PySpark Optimization, Null Handling and RDD Transformations

## Overview

On Week 4 Day 4, I practiced advanced PySpark concepts including DataFrame optimization, null value handling, partition management, caching techniques, data cleaning, and fundamental RDD transformations.

These exercises helped me understand how PySpark manages distributed data processing and improves DataFrame performance.

## Objective

The main objective of this practice was to improve my understanding of PySpark optimization techniques, partition management, null handling, data cleaning, and basic RDD transformations.

## Project Files

| File Name                       | Description                                                                                                        |
| ------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| `PySpark_DF_Practice_Ass-7.txt` | Contains exercises on partition management, caching, null handling, value replacement, and DataFrame optimization. |
| `PySpark_DF_Practice_Ass-8.txt` | Contains exercises on RDD transformations such as `map()`, `flatMap()`, and `reduceByKey()`.                       |

## Operations Practiced

### Partition Management

* Managed DataFrame partitions using `repartition()`.
* Reduced the number of partitions using `coalesce()`.
* Compared the behavior of `repartition()` and `coalesce()`.
* Observed how partition changes affect DataFrame processing.

### Performance Optimization

* Improved DataFrame performance using `cache()`.
* Compared execution before and after caching.
* Released cached data using `unpersist()`.

### Null Value Handling

* Filled missing values using `fillna()` and `na.fill()`.
* Removed records containing null values using `na.drop()`.
* Replaced missing values with suitable default values.

### Data Cleaning

* Replaced existing values using `replace()`.
* Standardized values in city, department, and gender columns.
* Improved data consistency through value replacement.

### RDD Transformations

* Applied `map()` for element-wise transformations.
* Used `flatMap()` to flatten nested collections.
* Aggregated records using `reduceByKey()`.
* Generated department-level summaries using RDD transformations.

## PySpark Functions Practiced

The following PySpark functions and operations were used:

* `repartition()`
* `coalesce()`
* `cache()`
* `unpersist()`
* `fillna()`
* `na.fill()`
* `na.drop()`
* `replace()`
* `map()`
* `flatMap()`
* `reduceByKey()`

## Important Concepts Learned

* Managing DataFrame partitions.
* Understanding the difference between `repartition()` and `coalesce()`.
* Improving DataFrame performance using caching.
* Releasing cached memory using `unpersist()`.
* Handling missing values in DataFrames.
* Cleaning and standardizing data.
* Understanding the basics of RDD transformations.
* Performing aggregation using `reduceByKey()`.
* Working with distributed data processing concepts.

## Technologies Used

* Databricks
* PySpark
* Apache Spark
* PySpark DataFrame API
* RDD API

## Learning Outcome

Through this practice, I improved my understanding of PySpark optimization techniques, partition management, null value handling, data cleaning, and RDD transformations.

These exercises also helped me understand how DataFrame optimization and RDD operations contribute to efficient distributed data processing.

## Week 4 - Day 4 Progress

Completed Week 4 Day 4 of my PySpark learning journey by practicing DataFrame optimization, null handling, partition management, and RDD transformations using PySpark.
