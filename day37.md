# Simple Python Project – Day 37

## About
This project demonstrates basic use of loops and conditional logic in Python.
It focuses on identifying and printing all numbers within a range that are divisible by a given value.
The goal is to strengthen understanding of iteration and modular arithmetic.

---

## Python Code

```python
# Day 37: Print numbers divisible by a given value within a range

def print_divisible(start, end, divisor):
    for num in range(start, end + 1):
        if num % divisor == 0:
            print(num)


print("Numbers divisible by 3:")
print_divisible(1, 20, 3)
