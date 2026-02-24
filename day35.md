# Simple Python Project – Day 35

## About
This project demonstrates basic use of loops and accumulation logic in Python.
It focuses on calculating the average of numbers stored in a list.
The goal is to reinforce list traversal, arithmetic operations, and function usage.

---

## Python Code

```python
# Day 35: Calculate average of elements in a list

def calculate_average(numbers):
    total = 0

    for num in numbers:
        total += num

    average = total / len(numbers)
    return average


values = [10, 20, 30, 40, 50]
result = calculate_average(values)

print("List:", values)
print("Average value:", result)
