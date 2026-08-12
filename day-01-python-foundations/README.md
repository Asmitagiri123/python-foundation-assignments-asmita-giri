# Day 1: Python Foundations

## Topics Covered

- Variables
- Data types
- String methods
- Operators
- Conditional statements

## Exercises

1. Sales Summary
2. Data Quality Checker
3. File Validator
4. Customer Record Cleaner
5. Pipeline Health Status
6. Dataset Access Decision

## How to Run

```bash
python exercise-01-sales-summary.py
```

## What I Learned

- Using variables and f-strings together makes it so much easier to calculate stuff and print it out in a clean, readable way instead of messy concatenation
- if / elif / else logic is actually pretty intuitive once you start using it to classify real things, like sorting data quality into Excellent, Acceptable, or Needs Cleaning
- `.strip()`, `.lower()`, and `.endswith()` are lifesavers when you're dealing with user input that could be typed in any random case
- `.title()` is great for cleaning up names and cities that come in all messed up with random capitalization and extra spaces
- Ternary expressions are basically a shortcut for writing simple if-else in one line, and honestly they make the code look cleaner
- Combining conditions with `and` lets you build rules that depend on more than one thing being true at once, which is closer to how real-world checks actually work

## Challenges Faced

- The Pipeline Health Status exercise tripped me up a bit — I had a case where the failure rate was low but the runtime was too high, and I had to really stop and think about why that still shouldn't count as "Healthy"
- I almost used `or` instead of `and` while combining conditions, which would've completely changed the result — small mistake but it taught me to slow down and read the logic carefully
- Testing the File Validator with different letter cases (uppercase, lowercase, mixed) made me realize how easy it is to overlook input formatting if you're not careful
