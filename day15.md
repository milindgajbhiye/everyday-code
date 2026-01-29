# Simple Python Project – Day 15

## About
This project focuses on basic numeric operations and function usage in Python.
It demonstrates how to calculate a result step by step using clear and simple logic.
The aim is to strengthen understanding of functions and arithmetic operations through daily practice.

---

## Python Code

```python
# Day 15: Calculate factorial of a number

def factorial(n):
    result = 1

    for i in range(1, n + 1):
        result *= i

    return result


number = 5
fact = factorial(number)

print("Number:", number)
print("Factorial:", fact)
