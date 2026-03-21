# Simple Python Project – Day 55

## About
This project focuses on basic list traversal and comparison logic in Python.
It demonstrates how to find the largest number in a list without using built-in functions.
The goal is to practice loops and understand how values can be compared step by step.

---

## Python Code

```python
# Day 55: Find the largest number in a list without using built-in functions

def find_largest(numbers):
    if len(numbers) == 0:
        return None

    largest = numbers[0]

    for num in numbers:
        if num > largest:
            largest = num

    return largest


values = [3, 7, 1, 9, 4, 6, 2]
result = find_largest(values)

print("List:", values)
print("Largest number:", result)
```
