# Simple Python Project – Day 19

## About
This project focuses on using basic exception handling in Python.
It demonstrates how to handle runtime errors gracefully without stopping the program.
The goal is to understand how try–except blocks help make programs more robust.

---

## Python Code

```python
# Day 19: Handle division by zero using exception handling

def safe_division(a, b):
    try:
        result = a / b
        print("Result:", result)
    except ZeroDivisionError:
        print("Error: Division by zero is not allowed")


safe_division(10, 2)
safe_division(10, 0)
