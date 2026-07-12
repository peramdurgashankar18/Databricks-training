# Day 2: SQL Date Manipulation

## Overview

On Day 2, I learned about SQL date and time functions. These functions are useful for extracting date information, performing date calculations, formatting dates, and working with timestamps.

## Date and Time Functions

### 1. CURRENT_DATE

The `CURRENT_DATE` function returns the current date.

**Syntax:**
`CURRENT_DATE`

**Example:**
`SELECT CURRENT_DATE;`

**Output Example:**
`2026-05-17`

---

### 2. CURRENT_TIMESTAMP

The `CURRENT_TIMESTAMP` function returns the current date and time.

**Syntax:**
`CURRENT_TIMESTAMP`

**Example:**
`SELECT CURRENT_TIMESTAMP;`

**Output Example:**
`2026-05-17 14:30:45`

---

### 3. DATE()

The `DATE()` function extracts the date portion from a date and time value.

**Example:**
`DATE('2026-05-17 14:30:45')`

**Output:**
`2026-05-17`

---

### 4. YEAR()

The `YEAR()` function extracts the year from a date.

**Example:**
`YEAR('2026-05-17')`

**Output:**
`2026`

---

### 5. MONTH()

The `MONTH()` function extracts the month number from a date.

**Example:**
`MONTH('2026-05-17')`

**Output:**
`5`

---

### 6. DAY()

The `DAY()` function extracts the day of the month from a date.

**Example:**
`DAY('2026-05-17')`

**Output:**
`17`

---

### 7. DAYOFWEEK()

The `DAYOFWEEK()` function returns the weekday number for a given date.

In MySQL:

* `1` represents Sunday.
* `7` represents Saturday.

**Example:**
`DAYOFWEEK('2026-05-17')`

**Output:**
`1`

---

### 8. DATE_ADD()

The `DATE_ADD()` function adds a specified time interval to a date.

**Syntax:**
`DATE_ADD(date, INTERVAL value unit)`

**Example:**
`DATE_ADD('2026-05-17', INTERVAL 5 DAY)`

**Output:**
`2026-05-22`

---

### 9. DATE_SUB()

The `DATE_SUB()` function subtracts a specified time interval from a date.

**Syntax:**
`DATE_SUB(date, INTERVAL value unit)`

**Example:**
`DATE_SUB('2026-05-17', INTERVAL 5 DAY)`

**Output:**
`2026-05-12`

---

### 10. DATEDIFF()

The `DATEDIFF()` function calculates the difference between two dates in days.

**Syntax:**
`DATEDIFF(date1, date2)`

**Example:**
`DATEDIFF('2026-05-20', '2026-05-17')`

**Output:**
`3`

---

### 11. DATE_FORMAT()

The `DATE_FORMAT()` function formats a date using a specified format.

**Syntax:**
`DATE_FORMAT(date, format)`

**Example:**
`DATE_FORMAT('2026-05-17', '%Y-%m-%d')`

**Output:**
`2026-05-17`

---

### 12. FROM_UNIXTIME()

The `FROM_UNIXTIME()` function converts a Unix timestamp into a readable date and time value.

**Syntax:**
`FROM_UNIXTIME(unix_timestamp)`

**Example:**
`FROM_UNIXTIME(1684329600)`

The exact output can depend on the database server's time zone settings.

## Important Concepts Learned

* Extracting year, month, and day from dates.
* Working with the current date and timestamp.
* Adding and subtracting date intervals.
* Calculating the difference between dates.
* Formatting dates into readable formats.
* Converting Unix timestamps.
* Understanding weekday values.

## Practice Areas

* Date extraction and formatting
* Date arithmetic
* Time interval calculations
* Timestamp conversion
* Date comparison and filtering
* Time-based data analysis

## Day 2 Progress

Completed Day 2 of my SQL learning journey by understanding date manipulation functions and how to perform date-based operations in SQL.
