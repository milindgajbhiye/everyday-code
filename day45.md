# Simple Python Project – Day 45

## About
This project focuses on basic string analysis in Python.
It demonstrates how to count the number of digits present in a given string.
The goal is to practice string traversal and the use of built-in character checking methods.

---

## Python Code

```python
# Day 45: Count digits in a string

def count_digits(text):
    digit_count = 0

    for char in text:
        if char.isdigit():
            digit_count += 1

    return digit_count


sample_text = "Python123Practice456"
result = count_digits(sample_text)

print("Text:", sample_text)
print("Number of digits:", result)
