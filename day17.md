# Simple Python Project – Day 17

## About
This project focuses on checking whether a given number is a prime number.
It demonstrates how to use loops and conditional logic to solve a basic mathematical problem.
The goal is to improve logical thinking and understand how conditions work in real scenarios.

---

## Python Code

```python
# Day 17: Check if a number is prime

def is_prime(number):
    if number <= 1:
        return False

    for i in range(2, number):
        if number % i == 0:
            return False

    return True


num = 11

if is_prime(num):
    print(num, "is a prime number")
else:
    print(num, "is not a prime number")
