# Simple Python Project – Day 25

## About
This project demonstrates basic use of the `range` function and summation logic.
It focuses on calculating the sum of natural numbers up to a given value.
The goal is to reinforce loop usage and arithmetic operations in Python.

---

## Python Code

```python
# Day 25: Calculate sum of first N natural numbers

def sum_natural_numbers(n):
    total = 0

    for i in range(1, n + 1):
        total += i

    return total


number = 10
result = sum_natural_numbers(number)

print("Number:", number)
print("Sum of natural numbers:", result)
