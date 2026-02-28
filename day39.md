# Simple Python Project – Day 39

## About
This project focuses on basic use of nested loops in Python.
It demonstrates how to generate a simple multiplication grid.
The goal is to understand how loops can work inside other loops to create structured output.

---

## Python Code

```python
# Day 39: Print a simple multiplication grid

def print_multiplication_grid(size):
    for i in range(1, size + 1):
        for j in range(1, size + 1):
            print(i * j, end=" ")
        print()


print_multiplication_grid(5)
