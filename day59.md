# Simple Python Project – Day 59

## About
This project focuses on basic list operations and counting logic in Python.
It demonstrates how to find the second largest number in a list.
The goal is to practice sorting, list manipulation, and simple comparisons.

---

## Python Code

```python
# Day 59: Find the second largest number in a list

def second_largest(numbers):
    unique_numbers = list(set(numbers))
    unique_numbers.sort()

    return unique_numbers[-2]


values = [10, 5, 20, 8, 20, 15]
result = second_largest(values)

print("List:", values)
print("Second largest number:", result)
