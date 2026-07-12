# Day 5: SQL NULL Functions

## Overview

On Day 5, I learned how to handle `NULL` values in SQL. A `NULL` value represents missing, unknown, or unavailable data. Proper NULL handling is important for writing accurate SQL queries and managing incomplete data.

## NULL Functions and Operators

### 1. IS NULL

The `IS NULL` operator is used to check whether a column contains a NULL value.

**Syntax:**
`column_name IS NULL`

**Example:**
`WHERE email IS NULL`

---

### 2. IS NOT NULL

The `IS NOT NULL` operator checks whether a column contains a non-NULL value.

**Syntax:**
`column_name IS NOT NULL`

**Example:**
`WHERE email IS NOT NULL`

---

### 3. COALESCE()

The `COALESCE()` function returns the first non-NULL value from a list of values.

**Syntax:**
`COALESCE(value1, value2, value3, ...)`

**Example:**
`COALESCE(phone, mobile, 'No Contact')`

This returns the first available contact value.

---

### 4. IFNULL() / ISNULL()

These functions are used to replace NULL values with a specified default value. Function availability and syntax depend on the SQL database system.

**Example:**
`IFNULL(age, 0)`

If `age` is NULL, the result will be `0`.

---

### 5. NULLIF()

The `NULLIF()` function returns NULL when two expressions are equal.

**Syntax:**
`NULLIF(expression1, expression2)`

**Example:**
`NULLIF(salary, 0)`

If the salary is `0`, the function returns NULL.

---

### 6. NVL()

The `NVL()` function is commonly used in Oracle to replace a NULL value with another value.

**Syntax:**
`NVL(expression1, expression2)`

**Example:**
`NVL(commission, 0)`

---

### 7. CASE WHEN

The `CASE` statement can be used to handle NULL values using conditional logic.

**Example:**
`CASE WHEN age IS NULL THEN 'Unknown' ELSE 'Available' END`

---

### 8. COUNT(*) vs COUNT(column)

* `COUNT(*)` counts all rows.
* `COUNT(column)` counts only rows where the specified column is not NULL.

---

### 9. Comparing NULL Values

NULL values cannot be checked using the normal equality operator.

Incorrect:
`column_name = NULL`

Correct:
`column_name IS NULL`

SQL follows three-valued logic, so comparisons involving NULL usually produce an `UNKNOWN` result.

## Important Concepts Learned

* NULL is different from `0`, an empty string, and `FALSE`.
* Arithmetic operations involving NULL generally return NULL.
* Aggregate functions such as `SUM()` and `AVG()` ignore NULL values.
* `COUNT(column)` ignores NULL values.
* `DISTINCT` typically treats multiple NULL values as a single distinct group.
* `IS NULL` and `IS NOT NULL` should be used to check NULL values.

## Practice Areas

* Handling missing data
* Replacing NULL values with default values
* Filtering NULL and non-NULL records
* Using NULL values in conditional queries
* Understanding NULL behavior in aggregate functions
* Improving data quality through proper NULL handling

## Day 5 Progress

Completed Day 5 of my SQL learning journey by understanding NULL values and commonly used NULL-handling functions.
