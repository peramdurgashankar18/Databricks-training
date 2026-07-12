# Day 6: SQL Regular Expressions (REGEX)

## Overview

On Day 6, I learned about Regular Expressions (REGEX) and how they can be used in SQL for advanced pattern matching and text processing.

Regular expressions are useful for searching, validating, extracting, and transforming text based on specific patterns.

## REGEX Functions and Operators

### 1. REGEXP

The `REGEXP` operator checks whether a string matches a specified regular expression pattern.

**Syntax:**
`string REGEXP pattern`

**Example:**
`'john123' REGEXP '^[a-z]+[0-9]+$'`

**Result:**
`TRUE`

---

### 2. RLIKE

The `RLIKE` operator is used for regular expression pattern matching.

In MySQL, `RLIKE` is a synonym for `REGEXP`.

**Syntax:**
`string RLIKE pattern`

**Example:**
`email RLIKE '[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+'`

---

### 3. REGEXP_LIKE()

The `REGEXP_LIKE()` function checks whether a string matches a regular expression pattern.

**Syntax:**
`REGEXP_LIKE(string, pattern)`

**Example:**
`REGEXP_LIKE('test@example.com', '^[a-zA-Z0-9]+@')`

The function returns a result based on whether the pattern matches the given string.

---

### 4. REGEXP_EXTRACT()

The `REGEXP_EXTRACT()` function extracts text that matches a regular expression pattern.

**Syntax:**
`REGEXP_EXTRACT(string, pattern)`

**Example:**
`REGEXP_EXTRACT('john_doe_123', '[0-9]+')`

**Output:**
`123`

Function availability may depend on the SQL database system.

---

### 5. REGEXP_EXTRACT_ALL()

The `REGEXP_EXTRACT_ALL()` function extracts all values that match a specified pattern.

**Syntax:**
`REGEXP_EXTRACT_ALL(string, pattern)`

The result may be returned as a collection or array depending on the SQL database system.

---

### 6. REGEXP_REPLACE()

The `REGEXP_REPLACE()` function replaces text that matches a regular expression pattern.

**Syntax:**
`REGEXP_REPLACE(string, pattern, replacement)`

**Example:**
`REGEXP_REPLACE('john123mary456', '[0-9]+', 'X')`

**Output:**
`johnXmaryX`

---

### 7. LIKE

The `LIKE` operator performs simple pattern matching using SQL wildcard characters.

The commonly used wildcards are:

* `%` — Matches zero or more characters.
* `_` — Matches a single character.

**Example:**
`'john@domain.com' LIKE '%@%.com'`

`LIKE` is useful for simple patterns, while REGEX provides more advanced pattern-matching capabilities.

## Common REGEX Patterns

* `^` — Start of a string.
* `$` — End of a string.
* `.` — Matches any single character.
* `*` — Matches zero or more occurrences.
* `+` — Matches one or more occurrences.
* `?` — Matches zero or one occurrence.
* `[abc]` — Matches `a`, `b`, or `c`.
* `[a-z]` — Matches characters from `a` to `z`.
* `[^abc]` — Matches characters except `a`, `b`, or `c`.
* `(a|b)` — Matches either `a` or `b`.
* `\d` — Represents a digit in supported REGEX engines.
* `\D` — Represents a non-digit.
* `\w` — Represents a word character.
* `\s` — Represents whitespace.
* `\.` — Matches a literal dot.

REGEX syntax and supported patterns may vary depending on the SQL database system.

## REGEX Use Cases

### 1. Email Pattern Validation

REGEX can be used to check whether an email follows a basic expected format.

**Pattern:**
`^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$`

---

### 2. Phone Number Pattern Validation

REGEX can validate phone numbers that follow a specific format.

**Pattern:**
`^\d{3}-?\d{3}-?\d{4}$`

---

### 3. URL Pattern Matching

REGEX can be used to identify HTTP and HTTPS URLs.

**Pattern:**
`^https?://[^\s]+$`

---

### 4. Extracting Numbers from Text

Numbers can be identified inside a string using a digit pattern.

**Pattern:**
`\d+`

---

### 5. Extracting a Domain from an Email

REGEX can identify the text after the `@` symbol.

**Pattern:**
`@(.+)$`

## Important Concepts Learned

* Understanding regular expression patterns.
* Matching text using REGEX.
* Validating structured text data.
* Extracting information from strings.
* Replacing text using patterns.
* Understanding the difference between `LIKE` and REGEX.
* Using special REGEX characters and character classes.

## Practice Areas

* Pattern matching with REGEX
* Email and phone number validation
* URL pattern matching
* Text extraction
* Text transformation
* Complex string operations
* SQL data cleaning

## Day 6 Progress

Completed Day 6 of my SQL learning journey by understanding Regular Expressions and applying REGEX patterns for text searching, validation, extraction, and transformation.
