# Simple Python Project – Day 57

## About
This project focuses on basic list processing and logical checks in Python.
It demonstrates how to find all duplicate elements in a list.
The goal is to practice iteration, condition checking, and handling repeated values.

---

## Python Code

```python
# Day 57: Find duplicate elements in a list

def find_duplicates(items):
    seen = set()
    duplicates = set()

    for item in items:
        if item in seen:
            duplicates.add(item)
        else:
            seen.add(item)

    return list(duplicates)


values = [1, 2, 3, 2, 4, 5, 1, 6]
result = find_duplicates(values)

print("Original list:", values)
print("Duplicate elements:", result)
