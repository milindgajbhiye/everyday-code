# Simple Python Project – Day 41

## About
This project focuses on using Python lists and basic logical conditions to separate data.
It demonstrates how to divide numbers into two categories: even and odd.
The goal is to practice list traversal and simple classification logic.

---

## Python Code

```python
# Day 41: Separate even and odd numbers from a list

def separate_even_odd(numbers):
    even_numbers = []
    odd_numbers = []

    for num in numbers:
        if num % 2 == 0:
            even_numbers.append(num)
        else:
            odd_numbers.append(num)

    return even_numbers, odd_numbers


values = [1, 2, 3, 4, 5, 6, 7, 8]
even_list, odd_list = separate_even_odd(values)

print("Original list:", values)
print("Even numbers:", even_list)
print("Odd numbers:", odd_list)
