# Simple Python Project – Day 11

## About
This project continues my daily Python practice with a focus on lists and conditional logic.
It demonstrates how to filter data from a list based on a simple condition.
The aim is to improve understanding of iteration and decision making in Python through small, clear examples.

---

## Python Code

```python
# Day 11: Extract even numbers from a list

def get_even_numbers(numbers):
    even_numbers = []

    for num in numbers:
        if num % 2 == 0:
            even_numbers.append(num)

    return even_numbers


values = [3, 6, 9, 12, 15, 18]
result = get_even_numbers(values)

print("Even numbers in the list:", result)
