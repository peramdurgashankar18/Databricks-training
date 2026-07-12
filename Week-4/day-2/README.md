# Week 4 - Day 2: Advanced PySpark DataFrame Transformations

## Overview

On Week 4 Day 2, I practiced advanced PySpark DataFrame transformations involving multiple datasets, column transformations, array processing, string operations, and schema management.

The exercises helped me understand how different DataFrame operations can be combined for data processing and analysis.

## Objective

The main objective of this practice was to improve my understanding of advanced PySpark DataFrame operations such as joins, unions, sampling, explode, split, concatenation, type casting, and aliasing.

## Project Files

| File Name                              | Purpose                                                                                      |
| -------------------------------------- | -------------------------------------------------------------------------------------------- |
| `PySpark_DataFrame_Practice_Ass-3.txt` | Contains exercises on joins, unions, sampling, explode, split, and concatenation operations. |
| `PySpark_DataFrame_Practice_Ass-4.txt` | Contains exercises on type casting, aliasing, and schema-related transformations.            |

## Operations Practiced

### Join Operations

* Practiced inner joins.
* Practiced left joins.
* Practiced right joins.
* Practiced full outer joins.
* Combined employee and department DataFrames.
* Retrieved manager information for employees.
* Worked with related data from multiple DataFrames.

### Union Operations

* Combined DataFrames using `union()`.
* Combined DataFrames using `unionByName()`.
* Compared `union()` and `unionByName()`.
* Worked with DataFrames containing different column orders.
* Handled missing columns using `allowMissingColumns=True`.

### Limit and Sampling

* Retrieved a limited number of records using `limit()`.
* Generated random samples using `sample()`.
* Practiced sampling with seed values.
* Applied sampling after filtering DataFrame records.

### Explode Transformation

* Expanded array elements into individual rows using `explode()`.
* Worked with employee skill arrays.
* Counted employee skills.
* Filtered employees based on specific skills.
* Created skill-based DataFrame results.

### Split Transformation

* Split date values into separate components.
* Extracted year, month, and day values.
* Split designation strings.
* Extracted specific values from text columns.
* Created new columns using split results.

### Concat and Concat_WS

* Combined multiple columns using `concat()`.
* Combined columns with separators using `concat_ws()`.
* Created employee labels.
* Generated descriptive text fields.
* Formatted column values using custom separators.

### Type Casting

* Converted columns to String data types.
* Converted columns to Integer data types.
* Converted columns to Double data types.
* Converted values to Date data types.
* Created calculated numeric columns.
* Practiced managing DataFrame column data types.

### Aliasing

* Renamed displayed columns using `alias()`.
* Applied aliases to aggregation results.
* Used aliases while working with joins.
* Improved the readability of DataFrame output.

## PySpark Functions Practiced

The following PySpark functions and operations were used:

* `join()`
* `union()`
* `unionByName()`
* `allowMissingColumns=True`
* `limit()`
* `sample()`
* `explode()`
* `split()`
* `concat()`
* `concat_ws()`
* `cast()`
* `alias()`
* `current_date()`
* `collect_list()`
* `rand()`

## Important Concepts Learned

* Combining related DataFrames using joins.
* Understanding different join types.
* Merging DataFrames using union operations.
* Handling different column orders and missing columns.
* Limiting and sampling DataFrame records.
* Processing array columns using `explode()`.
* Splitting string values into multiple components.
* Combining multiple column values.
* Converting DataFrame column data types.
* Using aliases to improve output readability.
* Working with DataFrame schemas.

## Technologies Used

* Databricks
* PySpark
* Apache Spark
* PySpark DataFrame API

## Learning Outcome

Through this practice, I improved my understanding of advanced PySpark DataFrame transformations.

I gained hands-on experience with joins, unions, sampling, array processing, string transformations, type casting, and schema-related DataFrame operations.

## Week 4 - Day 2 Progress

Completed Week 4 Day 2 of my PySpark learning journey by practicing advanced DataFrame transformations and applying multiple PySpark operations to structured datasets.
