# Day 1: SQL String Functions

## Overview

On Day 1, I learned about SQL string functions and how they are used to manipulate text data. These functions are useful for data cleaning, formatting, searching, and transforming string values.

## String Functions

### 1. UPPER()

The `UPPER()` function converts all characters in a string to uppercase.

**Syntax:**
`UPPER(string)`

**Example:**
`UPPER('hello')`

**Output:**
`HELLO`

---

### 2. LOWER()

The `LOWER()` function converts all characters in a string to lowercase.

**Syntax:**
`LOWER(string)`

**Example:**
`LOWER('HELLO')`

**Output:**
`hello`

---

### 3. LENGTH() / LEN()

The `LENGTH()` or `LEN()` function returns the number of characters in a string. The function name depends on the SQL database system.

**Syntax:**
`LENGTH(string)`

**Example:**
`LENGTH('hello')`

**Output:**
`5`

---

### 4. SUBSTRING() / SUBSTR()

The `SUBSTRING()` function extracts a specific part of a string.

**Syntax:**
`SUBSTRING(string, start_position, length)`

**Example:**
`SUBSTRING('hello', 1, 3)`

**Output:**
`hel`

---

### 5. CONCAT()

The `CONCAT()` function combines two or more strings into a single string.

**Syntax:**
`CONCAT(string1, string2, ...)`

**Example:**
`CONCAT('Hello', ' ', 'World')`

**Output:**
`Hello World`

---

### 6. TRIM()

The `TRIM()` function removes unwanted spaces from the beginning and end of a string.

`LTRIM()` removes leading spaces, while `RTRIM()` removes trailing spaces.

**Example:**
`TRIM('  hello  ')`

**Output:**
`hello`

---

### 7. REPLACE()

The `REPLACE()` function replaces occurrences of a substring with another value.

**Syntax:**
`REPLACE(string, old_substring, new_substring)`

**Example:**
`REPLACE('hello world', 'world', 'SQL')`

**Output:**
`hello SQL`

---

### 8. INSTR()

The `INSTR()` function finds the position of a substring inside a string.

**Syntax:**
`INSTR(string, substring)`

**Example:**
`INSTR('hello world', 'world')`

**Output:**
`7`

---

### 9. REVERSE()

The `REVERSE()` function reverses the characters of a string.

**Syntax:**
`REVERSE(string)`

**Example:**
`REVERSE('hello')`

**Output:**
`olleh`

---

### 10. INITCAP()

The `INITCAP()` function converts the first letter of each word to uppercase.

**Syntax:**
`INITCAP(string)`

**Example:**
`INITCAP('hello world')`

**Output:**
`Hello World`

## Important Concepts Learned

* Converting text between uppercase and lowercase.
* Finding the length of string values.
* Extracting specific portions of text.
* Combining multiple strings.
* Removing unnecessary spaces.
* Replacing text inside a string.
* Searching for substrings.
* Reversing string values.
* Formatting words using capitalization.

## Practice Areas

* Text manipulation and formatting
* Data cleaning and standardization
* String searching
* String concatenation
* Data transformation

## Day 1 Progress

Completed Day 1 of my SQL learning journey by understanding commonly used string functions and their applications in SQL queries.
