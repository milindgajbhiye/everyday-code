# Simple Python Project – Day 49

## About
This project demonstrates how to remove duplicate elements from a list while keeping the original order.
It helps practice list traversal and conditional checks in Python.

---

## Python Code

```python
# Day 49: Remove duplicates from a list while preserving order

def remove_duplicates(items):
    unique = []

    for item in items:
        if item not in unique:
            unique.append(item)

    return unique


values = [1, 2, 2, 3, 4, 4, 5, 1, 6]
result = remove_duplicates(values)

print("Original list:", values)
print("List without duplicates:", result)
