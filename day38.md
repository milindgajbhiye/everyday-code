# Simple Python Project – Day 38

## About
This project focuses on working with lists and basic sorting logic in Python.
It demonstrates how to sort a list in ascending order using a built-in method.
The goal is to understand how sorting works and how built-in functions simplify tasks.

---

## Python Code

```python
# Day 38: Sort a list in ascending order

def sort_list(numbers):
    numbers.sort()
    return numbers


values = [42, 7, 19, 3, 25]
result = sort_list(values)

print("Original list:", [42, 7, 19, 3, 25])
print("Sorted list:", result)
