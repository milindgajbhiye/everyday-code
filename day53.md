# Simple Python Project – Day 53

## About
This project focuses on basic list manipulation and reversing data in Python.
It demonstrates how to reverse a list without using built-in methods.
The goal is to practice loops and understand how data can be reordered manually.

---

## Python Code

```python
# Day 53: Reverse a list without using built-in functions

def reverse_list(items):
    reversed_items = []

    for i in range(len(items) - 1, -1, -1):
        reversed_items.append(items[i])

    return reversed_items


values = [1, 2, 3, 4, 5]
result = reverse_list(values)

print("Original list:", values)
print("Reversed list:", result)
