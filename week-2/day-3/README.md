# Day 3: SQL Number Manipulation

## Overview

On Day 3, I learned about SQL numeric functions and how they are used to perform mathematical calculations, rounding, and numeric transformations on data.

These functions are useful for data analysis, calculations, and processing numerical values.

## Number Functions

### 1. ROUND()

The `ROUND()` function rounds a number to a specified number of decimal places.

**Syntax:**
`ROUND(number, decimal_places)`

**Example:**
`ROUND(3.14159, 2)`

**Output:**
`3.14`

---

### 2. CEIL() / CEILING()

The `CEIL()` or `CEILING()` function rounds a number upward to the nearest integer.

**Syntax:**
`CEIL(number)`

**Example:**
`CEIL(3.2)`

**Output:**
`4`

---

### 3. FLOOR()

The `FLOOR()` function rounds a number downward to the nearest integer.

**Syntax:**
`FLOOR(number)`

**Example:**
`FLOOR(3.8)`

**Output:**
`3`

---

### 4. ABS()

The `ABS()` function returns the absolute value of a number.

**Syntax:**
`ABS(number)`

**Example:**
`ABS(-10)`

**Output:**
`10`

---

### 5. MOD()

The `MOD()` function returns the remainder after division.

**Syntax:**
`MOD(dividend, divisor)`

**Example:**
`MOD(10, 3)`

**Output:**
`1`

---

### 6. POWER()

The `POWER()` function raises a number to a specified power.

**Syntax:**
`POWER(base, exponent)`

**Example:**
`POWER(2, 3)`

**Output:**
`8`

---

### 7. SQRT()

The `SQRT()` function returns the square root of a number.

**Syntax:**
`SQRT(number)`

**Example:**
`SQRT(16)`

**Output:**
`4`

---

### 8. EXP()

The `EXP()` function returns the value of `e` raised to a specified power.

**Syntax:**
`EXP(number)`

**Example:**
`EXP(1)`

**Output:**
Approximately `2.71828`

---

### 9. LN() / LOG()

The `LN()` function calculates the natural logarithm of a number.

**Syntax:**
`LN(number)`

**Example:**
`LN(2.718281828)`

**Output:**
Approximately `1`

The behavior of `LOG()` may vary depending on the SQL database system.

---

### 10. LOG10()

The `LOG10()` function calculates the base-10 logarithm of a number.

**Syntax:**
`LOG10(number)`

**Example:**
`LOG10(100)`

**Output:**
`2`

---

### 11. SIGN()

The `SIGN()` function identifies whether a number is negative, zero, or positive.

It returns:

* `-1` for a negative number.
* `0` for zero.
* `1` for a positive number.

**Example:**
`SIGN(-5)`

**Output:**
`-1`

---

### 12. TRUNCATE()

The `TRUNCATE()` function removes decimal digits after a specified number of decimal places without rounding.

**Syntax:**
`TRUNCATE(number, decimal_places)`

**Example:**
`TRUNCATE(3.14159, 2)`

**Output:**
`3.14`

---

### 13. GREATEST()

The `GREATEST()` function returns the largest value from a list of values.

**Syntax:**
`GREATEST(value1, value2, value3, ...)`

**Example:**
`GREATEST(5, 10, 3)`

**Output:**
`10`

---

### 14. LEAST()

The `LEAST()` function returns the smallest value from a list of values.

**Syntax:**
`LEAST(value1, value2, value3, ...)`

**Example:**
`LEAST(5, 10, 3)`

**Output:**
`3`

## Important Concepts Learned

* Rounding numerical values.
* Finding ceiling and floor values.
* Working with absolute values.
* Calculating division remainders.
* Performing power and square root calculations.
* Working with exponential and logarithmic functions.
* Identifying positive and negative numbers.
* Truncating decimal values.
* Finding the greatest and smallest values.

## Practice Areas

* Basic mathematical operations
* Rounding and truncation
* Power and square root calculations
* Logarithmic functions
* Finding minimum and maximum values
* Decimal value management
* Numeric data transformation

## Day 3 Progress

Completed Day 3 of my SQL learning journey by understanding commonly used numeric functions and their applications in SQL queries.
