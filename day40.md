# Simple Python Project – Day 40

## About
This project focuses on working with lists and basic searching logic in Python.
It demonstrates how to check whether a specific element exists in a list.
The goal is to strengthen understanding of iteration and conditional checks.

---

## Python Code

```python
# Day 40: Check if an element exists in a list

def element_exists(numbers, target):
    for num in numbers:
        if num == target:
            return True
    return False


values = [5, 12, 7, 20, 9]
target_value = 7

if element_exists(values, target_value):
    print("Element found in the list")
else:
    print("Element not found in the list")
