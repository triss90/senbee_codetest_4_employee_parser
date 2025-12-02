# PHP Code Test

Thank you for your interest in joining the Senbee team.  
This short assignment is designed to evaluate your understanding of **basic PHP** without relying on frameworks or external libraries. We want to see how you think, how you structure code, and how you explain your decisions.

Please read the instructions carefully.

---

## 📁 Overview

Your task is to build a small, self-contained PHP script that reads employee data from a CSV file and displays it on a webpage with simple filtering and grouping options.

The assignment consists of multiple steps. Each one builds on the previous, and all must be completed to finish the test.

No frameworks, no Composer, and no external packages.  
Use only plain PHP, HTML, and basic CSS if you wish.

Please **do not use AI tools** to generate or assist with your solution.

---

## 🧪 The Assignment

### 1. Load and Parse a CSV File

Create a function that reads a local file named **`employees.csv`** and returns its contents as an array of associative arrays.

Requirements:

- Assume the first row contains column headers.
- Do **not** use `fgetcsv`.
- Implement your own CSV parsing logic.
- The function should handle:
  - Splitting rows
  - Splitting columns
  - Mapping header fields to row values

The file `employees.csv` will be provided for you.

---

### 2. Display the Employee List

Create a simple webpage that:

- Loads the data using your CSV parsing function.
- Displays the results in an HTML table.
- Does not use external styling or libraries.

The table must be generated using your PHP code.

---

### 3. Add a Search Filter (No JavaScript)

Extend the page with a search field:

- Add an input named `search`.
- When the form is submitted, filter rows that contain the search term **anywhere** (case insensitive).
- The filtering must be done in PHP.

---

### 4. Add “Group by Department”

Add a dropdown named `group_by` with two options:

- `no` (default)
- `yes`

When `group_by=yes`, group the employees by their department and render each group with a simple heading.

You may assume that the CSV file contains a `department` column.

---

### 5. Write a Short Explanation

Create a file named **`EXPLAIN.md`** that briefly describes:

1. How your CSV parsing function works.
2. How your search filter is implemented.
3. How your grouping logic is structured.

We are not testing your writing skills, but your understanding of your own code.

---

## 📦 Deliverables

When finished, submit a folder containing:

- `index.php` (or similar)
- Any additional PHP files you create
- `employees.csv`
- `EXPLAIN.md`
- (Optional) a small CSS file for base styling

Please ensure your code runs out of the box with no dependencies other than PHP.

---

## ✔ Evaluation Criteria

We look for:

- Clear, readable code
- Correct functionality
- Logical structure
- Understanding of PHP basics
- Ability to solve small problems without external tools

This assignment is intentionally simple, and we expect concise, clean solutions.

---

If you have any questions about the assignment, please let us know.
