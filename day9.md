# Simple Python Project – Day 9

## About
This project focuses on working with lists and basic iteration in Python.
It demonstrates how to process multiple values using loops.

---

## Python Code

```python
# Day 9: Find the sum of elements in a list

def list_sum(numbers):
    total = 0
    for num in numbers:
        total += num
    return total


values = [5, 10, 15, 20]
result = list_sum(values)
print("Sum of list elements:", result)
