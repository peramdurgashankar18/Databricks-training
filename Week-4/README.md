# Week 4: PySpark DataFrame Transformations and Analytics

## Overview

During Week 4, I practiced PySpark DataFrame transformations, analytical operations, optimization concepts, RDD transformations, and Window Functions.

The week included multiple DataFrame practice assignments and an Employee Salary Analytics mini project.

## Week Objective

The main objective of Week 4 was to improve my understanding of PySpark DataFrame operations and apply different transformation and analytical techniques to structured datasets.

Throughout the week, I practiced DataFrame selection, filtering, joins, unions, conditional transformations, Window Functions, partition management, caching, RDD operations, and aggregation techniques.

## Weekly Learning Overview

| Day       | Learning Focus                                | Topics Covered                                                                                          |
| --------- | --------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| **Day 1** | Core DataFrame Transformations                | DataFrame Creation, Select, Filter, withColumn, Sorting, GroupBy, Aggregations                          |
| **Day 2** | Advanced DataFrame Transformations            | Join, Union, UnionByName, Sampling, Explode, Split, Concat, Cast, Alias                                 |
| **Day 3** | Conditional and Analytical Operations         | Lit, When, Substring, Regexp Replace, Like, IsIn, Between, Pivot, Unpivot, Window Functions             |
| **Day 4** | Optimization and RDD Transformations          | Repartition, Coalesce, Cache, Null Handling, Replace, Map, FlatMap, ReduceByKey                         |
| **Day 5** | Advanced Analytics and Distributed Processing | MapPartitions, ZipWithIndex, Cross Join, Set Operations, Cube, Rollup, Broadcast Join, Array Processing |
| **Day 6** | Mini Project                                  | Employee Salary Analytics                                                                               |

## Week Highlights

| Category                     |   Completed   |
| ---------------------------- | :-----------: |
| Practice Sessions            |     **6**     |
| Assignments                  |     **10**    |
| Practice Files               |     **11**    |
| Mini Projects                |     **1**     |
| PySpark DataFrame Operations |  **Multiple** |
| DataFrame and RDD APIs       | **Practiced** |

## Technical Skills Practiced

### DataFrame Operations

Practiced different PySpark DataFrame operations, including:

* DataFrame creation
* Column selection
* Data filtering
* Column creation
* Column renaming
* Sorting and ordering
* Grouping and aggregation
* Join operations
* Union operations

### Conditional and String Operations

Applied conditional and string transformations using:

* `lit()`
* `when()`
* `otherwise()`
* `substring()`
* `regexp_replace()`
* `like()`
* `isin()`
* `between()`
* `split()`
* `concat()`
* `concat_ws()`

These operations helped me understand how to create conditional columns and process string-based data.

### Window Functions

Practiced analytical Window Functions such as:

* `rank()`
* `dense_rank()`
* `row_number()`
* `lead()`
* `lag()`

Used Window Functions for employee ranking and row-level analytical operations.

### Data Reshaping

Worked with different data reshaping techniques:

* `pivot()`
* `unpivot()`
* `stack()`
* `explode()`
* `explode_outer()`

These operations helped me understand how DataFrame structures can be transformed for analysis.

### Partition Management and Caching

Practiced PySpark optimization concepts using:

* `repartition()`
* `coalesce()`
* `cache()`
* `unpersist()`
* `broadcast()`

Compared partition management techniques and practiced caching and broadcast join concepts.

### Null Handling and Data Cleaning

Handled missing and inconsistent data using:

* `fillna()`
* `na.fill()`
* `na.drop()`
* `replace()`

Practiced replacing missing values and standardizing DataFrame values.

### RDD Transformations

Practiced fundamental RDD operations such as:

* `map()`
* `flatMap()`
* `mapPartitions()`
* `reduceByKey()`
* `zipWithIndex()`

These exercises improved my understanding of basic RDD transformations and partition-based processing.

### Aggregation and Reporting

Created analytical results using:

* `groupBy()`
* `agg()`
* `sum()`
* `avg()`
* `min()`
* `max()`
* `count()`
* `cube()`
* `rollup()`

Practiced grouped, hierarchical, and multidimensional aggregation operations.

## Repository Structure

```text
Week4/
│
├── Day1/
│   ├── PySpark_DataFrame_Practice_Ass-1.txt
│   ├── PySpark_DataFrame_Practice_Ass-2.txt
│   └── README.md
│
├── Day2/
│   ├── PySpark_DataFrame_Practice_Ass-3.txt
│   ├── PySpark_DataFrame_Practice_Ass-4.txt
│   └── README.md
│
├── Day3/
│   ├── PySpark_DF_Practice_Ass-5.txt
│   ├── PySpark_DF_Practice_Ass-6.txt
│   └── README.md
│
├── Day4/
│   ├── PySpark_DF_Practice_Ass-7.txt
│   ├── PySpark_DF_Practice_Ass-8.txt
│   └── README.md
│
├── Day5/
│   ├── PySpark_DF_Practice_Ass-9.txt
│   ├── PySpark_DF_Practice_Ass-10.txt
│   └── README.md
│
├── Day6/
│   ├── MiniProject_Advanced-1.txt
│   └── README.md
│
└── README.md
```

## Datasets Used

The assignments used sample datasets to practice different PySpark operations.

### Employee Data

* Employee information
* Salary details
* Employee age and city
* Joining date
* Department information

### Department Data

* Department details
* Manager information

### Skills Data

* Employee skills
* Array-based column values

### Salary Analytics Data

* Employee salary information
* Department-level salary analysis
* City-wise salary analysis
* Joining year analysis

## Practical Tasks Completed

* Created and explored PySpark DataFrames.
* Selected and filtered employee records.
* Added and renamed DataFrame columns.
* Implemented different join operations.
* Combined DataFrames using union operations.
* Created Pivot and Unpivot results.
* Applied Window Functions for employee ranking.
* Handled missing values.
* Practiced caching and partition management.
* Processed array data using Explode operations.
* Performed Cube and Rollup aggregations.
* Practiced RDD transformations.
* Used broadcast joins.
* Built an Employee Salary Analytics mini project.

## Technologies Used

* Apache Spark
* PySpark
* Databricks
* Python
* Git
* GitHub

## Skills Practiced

| Skill                     |   Status  |
| ------------------------- | :-------: |
| DataFrame Transformations | Completed |
| Filtering and Selection   | Completed |
| Join Operations           | Completed |
| Window Functions          | Completed |
| Pivot and Unpivot         | Completed |
| RDD Transformations       | Completed |
| Partition Management      | Completed |
| Null Value Handling       | Completed |
| Cube and Rollup           | Completed |
| Broadcast Join            | Completed |
| Mini Project              | Completed |

## Key Learnings

By the end of Week 4, I improved my understanding of:

* PySpark DataFrame transformations.
* Data selection and filtering.
* Join and union operations.
* Conditional DataFrame transformations.
* Window Functions and ranking operations.
* Pivoting and reshaping data.
* Partition management and caching.
* Null value handling and data cleaning.
* Basic RDD transformations.
* Cube and Rollup aggregations.
* Broadcast join concepts.
* Combining multiple PySpark operations for data analysis.

## Week Summary

Week 4 provided hands-on practice with PySpark DataFrame transformations, analytical operations, optimization concepts, Window Functions, and RDD transformations.

Completing the practice assignments and Employee Salary Analytics mini project helped me apply multiple PySpark concepts to structured datasets and strengthened my understanding of DataFrame-based data processing.

## Week 4 Progress

Successfully completed Week 4 of my PySpark learning journey by practicing DataFrame transformations, analytical functions, optimization concepts, RDD operations, and building an Employee Salary Analytics mini project.
