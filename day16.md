# Simple Python Project – Day 16

## About
This project focuses on working with lists and basic comparisons in Python.
It demonstrates how to find the largest value from a collection of numbers using simple logic.
The goal is to practice iteration, comparison, and function design in a clear and readable way.

---

## Python Code

```python
# Day 16: Find the maximum number in a list

def find_max(numbers):
    max_value = numbers[0]

    for num in numbers:
        if num > max_value:
            max_value = num

    return max_value


values = [12, 45, 7, 89, 23]
result = find_max(values)

print("List:", values)
print("Maximum value:", result)
