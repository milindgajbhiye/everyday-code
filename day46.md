# Simple Python Project – Day 46

## About
This project focuses on basic list processing and conditional logic in Python.
It demonstrates how to filter numbers from a list that are greater than a specified value.
The goal is to practice iteration, comparisons, and building a new list from existing data.

---

## Python Code

```python
# Day 46: Get numbers greater than a given value

def numbers_greater_than(numbers, threshold):
    result = []

    for num in numbers:
        if num > threshold:
            result.append(num)

    return result


values = [4, 12, 7, 25, 9, 30]
limit = 10

filtered_numbers = numbers_greater_than(values, limit)

print("Original list:", values)
print("Numbers greater than", limit, ":", filtered_numbers)
