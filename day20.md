# Simple Python Project – Day 20

## About
This project focuses on using sets in Python to work with unique values.
It demonstrates how sets automatically remove duplicate elements and how they can be used in simple operations.
The goal is to understand the importance of sets when working with unique data.

---

## Python Code

```python
# Day 20: Remove duplicate elements from a list using a set

def remove_duplicates(items):
    unique_items = set(items)
    return list(unique_items)


values = [1, 2, 3, 2, 4, 1, 5]
result = remove_duplicates(values)

print("Original list:", values)
print("List after removing duplicates:", result)
