# Simple Python Project – Day 27

## About
This project demonstrates basic use of loops and conditional logic to analyze numbers.
It focuses on counting how many numbers in a list are greater than a given value.
The goal is to strengthen understanding of iteration and comparisons in Python.

---

## Python Code

```python
# Day 27: Count numbers greater than a target value

def count_greater(numbers, target):
    count = 0

    for num in numbers:
        if num > target:
            count += 1

    return count


values = [4, 9, 1, 15, 7, 20]
target_value = 8

result = count_greater(values, target_value)

print("Numbers greater than", target_value, ":", result)
