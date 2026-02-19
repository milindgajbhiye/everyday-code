# Simple Python Project – Day 31

## About
This project demonstrates basic use of loops and arithmetic operations in Python.
It focuses on generating the multiplication table of a given number.
The goal is to practice iteration and formatted output.

---

## Python Code

```python
# Day 31: Print multiplication table of a number

def print_table(number):
    for i in range(1, 11):
        result = number * i
        print(f"{number} x {i} = {result}")


print_table(5)
