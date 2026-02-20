# Simple Python Project – Day 32

## About
This project focuses on basic list traversal and conditional logic in Python.
It demonstrates how to count how many elements in a list are divisible by a given number.
The goal is to strengthen understanding of loops and modular arithmetic.

---

## Python Code

```python
# Day 32: Count numbers divisible by a given value

def count_divisible(numbers, divisor):
    count = 0

    for num in numbers:
        if num % divisor == 0:
            count += 1

    return count


values = [10, 15, 20, 25, 30, 35]
divisor = 5

result = count_divisible(values, divisor)

print("List:", values)
print("Divisor:", divisor)
print("Count of divisible numbers:", result)
