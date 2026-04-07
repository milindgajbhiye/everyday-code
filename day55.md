# Simple Python Project – Day 55

## About
This project focuses on basic numeric logic and loops in Python.
It demonstrates how to generate Fibonacci numbers up to a given limit.
The goal is to practice iteration, variable updates, and sequence generation.

---

## Python Code

```python
# Day 55: Generate Fibonacci sequence up to N terms

def fibonacci(n):
    a, b = 0, 1
    sequence = []

    for _ in range(n):
        sequence.append(a)
        a, b = b, a + b

    return sequence


terms = 7
result = fibonacci(terms)

print("Number of terms:", terms)
print("Fibonacci sequence:", result)
