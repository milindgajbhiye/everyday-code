# Simple Python Project – Day 54

## About
This project focuses on basic list traversal and arithmetic in Python.
It demonstrates how to find the sum of all even numbers in a list.
The goal is to practice conditional checks and accumulation using loops.

---

## Python Code

```python
# Day 54: Find the sum of all even numbers in a list

def sum_even_numbers(numbers):
    total = 0

    for num in numbers:
        if num % 2 == 0:
            total += num

    return total


values = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
result = sum_even_numbers(values)

print("List:", values)
print("Sum of even numbers:", result)
