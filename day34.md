# Simple Python Project – Day 34

## About
This project focuses on basic numeric logic and conditional statements in Python.
It demonstrates how to determine whether a given year is a leap year.
The goal is to practice decision-making logic and arithmetic conditions.

---

## Python Code

```python
# Day 34: Check if a year is a leap year

def is_leap_year(year):
    if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
        return True
    else:
        return False


year = 2024

if is_leap_year(year):
    print(year, "is a leap year")
else:
    print(year, "is not a leap year")
