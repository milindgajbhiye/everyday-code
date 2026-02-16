# Simple Python Project – Day 29

## About
This project demonstrates basic list processing and conditional checks in Python.
It focuses on finding the smallest value in a list using simple comparison logic.
The goal is to reinforce iteration and decision-making fundamentals.

---

## Python Code

```python
# Day 29: Find the minimum number in a list

def find_min(numbers):
    min_value = numbers[0]

    for num in numbers:
        if num < min_value:
            min_value = num

    return min_value


values = [18, 3, 25, 7, 10]
result = find_min(values)

print("List:", values)
print("Minimum value:", result)
