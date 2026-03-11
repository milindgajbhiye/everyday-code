# Simple Python Project – Day 48

## About
This project focuses on basic numeric processing in Python.
It demonstrates how to calculate the sum of digits in a number.
The goal is to practice loops, arithmetic operations, and number manipulation.

---

## Python Code

```python
# Day 48: Calculate sum of digits of a number

def sum_of_digits(number):
    total = 0

    while number > 0:
        digit = number % 10
        total += digit
        number = number // 10

    return total


num = 12345
result = sum_of_digits(num)

print("Number:", num)
print("Sum of digits:", result)
      
