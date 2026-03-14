# Simple Python Project – Day 51

## About
This project focuses on basic list traversal and counting logic in Python.
It demonstrates how to count the number of positive and negative values in a list.
The goal is to practice conditional checks and simple data analysis using loops.

---

## Python Code

```python
# Day 51: Count positive and negative numbers in a list

def count_positive_negative(numbers):
    positive_count = 0
    negative_count = 0

    for num in numbers:
        if num > 0:
            positive_count += 1
        elif num < 0:
            negative_count += 1

    return positive_count, negative_count


values = [10, -4, 7, -9, 0, 15, -2]
positive, negative = count_positive_negative(values)

print("List:", values)
print("Positive numbers:", positive)
print("Negative numbers:", negative)
