# Day 1: Reading CSV Files Using PySpark

## Overview

On Day 1, I learned how to read CSV files using PySpark and display the data in Databricks.

This helped me understand the basics of working with PySpark DataFrames and loading external datasets.

## Files Used

The following CSV files were used:

* `Big Sales.csv`
* `empData.csv`

## PySpark Code

```python
# Reading Big Sales CSV File

df = spark.read.csv(
    "/Volumes/workspace/default/day1files/Big Sales.csv",
    header=True
)

df.show()


# Reading Employee Data CSV File

df2 = spark.read.csv(
    "/Volumes/workspace/default/day1files/empData.csv",
    header=True
)

df2.show()
```

## Code Explanation

### spark.read.csv()

The `spark.read.csv()` function is used to load CSV data into a PySpark DataFrame.

### header=True

The `header=True` option specifies that the first row of the CSV file contains column names.

### DataFrame

A DataFrame is a distributed collection of structured data organized into rows and columns.

### show()

The `show()` function displays the contents of a PySpark DataFrame.

**Example:**

```python
df.show()
```

## Concepts Learned

* Databricks Workspace
* Databricks Volumes
* Uploading CSV files
* Reading CSV files using PySpark
* PySpark DataFrames
* Using the `show()` function

## Output

Successfully loaded and displayed CSV data using PySpark in Databricks.

## Day 1 Progress

Completed Day 1 of my PySpark learning journey by understanding how to load CSV files into DataFrames and display data using PySpark in Databricks.
