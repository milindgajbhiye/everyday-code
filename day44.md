# Simple Python Project – Day 44

## About
This project demonstrates basic number processing in Python.
It focuses on calculating the sum of only the even numbers in a list.
The goal is to practice loops, conditional logic, and simple arithmetic operations.

---

## Python Code

```python
# Day 44: Calculate sum of even numbers in a list

def sum_even_numbers(numbers):
    total = 0

    for num in numbers:
        if num % 2 == 0:
            total += num

    return total


values = [3, 8, 5, 12, 7, 10]
result = sum_even_numbers(values)

print("List:", values)
print("Sum of even numbers:", result)
