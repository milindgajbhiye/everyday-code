# Simple Python Project – Day 26

## About
This project focuses on checking whether a string is a palindrome.
It demonstrates how to work with strings, reverse them, and compare values.
The goal is to strengthen string manipulation skills and logical thinking in Python.

---

## Python Code

```python
# Day 26: Check if a string is a palindrome

def is_palindrome(text):
    reversed_text = text[::-1]
    return text == reversed_text


word = "level"

if is_palindrome(word):
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
