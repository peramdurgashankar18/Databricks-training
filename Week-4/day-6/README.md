# Week 4 - Day 6: PySpark Mini Project - Employee Salary Analytics

## Overview

On Week 4 Day 6, I completed a PySpark mini project focused on employee salary analytics.

In this project, I applied PySpark DataFrame transformations, aggregation functions, conditional expressions, and Window Functions to analyze employee salary data and generate structured analytical reports.

## Objective

The main objective of this mini project was to apply the PySpark concepts I practiced during the previous sessions to an employee salary dataset.

The project focused on salary analysis, department-level calculations, employee ranking, and conditional salary classification.

## Project File

| File Name                    | Description                                                                                               |
| ---------------------------- | --------------------------------------------------------------------------------------------------------- |
| `MiniProject_Advanced-1.txt` | Contains the PySpark implementation for employee salary analysis using aggregations and Window Functions. |

## Analysis Performed

### Salary Analysis

* Identified the top three highest-paid employees in each department.
* Calculated the average employee salary for each city.
* Classified employees into Low, Medium, and High salary categories.

### Department Analysis

* Calculated department-wise average salaries.
* Compared employee salaries with their department's average salary.
* Identified employees earning more than their department's average salary.

### Joining Year Analysis

* Extracted employee joining years using `year()`.
* Generated salary reports based on joining year.
* Performed salary aggregation for employees grouped by joining year.

### Employee Ranking

* Ranked employees based on salary using `dense_rank()`.
* Used Window Functions to perform department-level ranking.
* Partitioned employee records by department using `partitionBy()`.
* Ordered employee salaries using `orderBy()`.

## PySpark Functions Practiced

The following PySpark functions and operations were used:

* `groupBy()`
* `avg()`
* `sum()`
* `year()`
* `when()`
* `otherwise()`
* `dense_rank()`
* `Window`
* `partitionBy()`
* `orderBy()`
* `withColumn()`
* `filter()`
* `alias()`

## Important Concepts Applied

* PySpark DataFrame transformations.
* Data aggregation.
* Conditional column creation.
* Salary classification.
* Department-level analysis.
* City-wise salary analysis.
* Joining year analysis.
* Window specifications.
* Employee ranking.
* Comparing row values with grouped averages.

## Technologies Used

* Databricks
* PySpark
* Apache Spark
* PySpark DataFrame API
* PySpark Window Functions

## Learning Outcome

Through this mini project, I applied multiple PySpark concepts to analyze employee salary data.

I improved my understanding of aggregation functions, conditional transformations, department-level analysis, and Window Functions.

The project also helped me understand how different DataFrame operations can be combined to generate analytical reports from structured employee data.

## Week 4 - Day 6 Progress

Completed Week 4 Day 6 of my PySpark learning journey by building an Employee Salary Analytics mini project using DataFrame transformations, aggregations, and Window Functions.
