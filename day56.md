# Simple Python Project – Day 56

## About
This project focuses on basic number checking and conditional logic in Python.
It demonstrates how to determine whether a number is an Armstrong number.
The goal is to practice loops, arithmetic operations, and logical conditions.

---

## Python Code

```python
# Day 56: Check if a number is an Armstrong number

def is_armstrong(number):
    num_str = str(number)
    power = len(num_str)
    total = 0

    for digit in num_str:
        total += int(digit) ** power

    return total == number


num = 153

if is_armstrong(num):
    print(num, "is an Armstrong number")
else:
    print(num, "is not an Armstrong number")
