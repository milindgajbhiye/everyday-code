# Simple Python Project – Day 43

## About
This project focuses on working with lists and simple data transformation in Python.
It demonstrates how to create a new list where each number from the original list is squared.
The goal is to practice list traversal and arithmetic operations.

---

## Python Code

```python
# Day 43: Create a list of squares

def square_numbers(numbers):
    squares = []

    for num in numbers:
        squares.append(num * num)

    return squares


values = [1, 2, 3, 4, 5]
result = square_numbers(values)

print("Original list:", values)
print("Squared list:", result)
