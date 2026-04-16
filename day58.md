# Simple Python Project – Day 58

## About
This project focuses on basic string processing and comparison in Python.
It demonstrates how to check whether a string is a palindrome while ignoring case sensitivity.
The goal is to improve understanding of string manipulation and normalization.

---

## Python Code

```python
# Day 58: Check if a string is a palindrome (case-insensitive)

def is_palindrome(text):
    normalized = text.lower()
    reversed_text = normalized[::-1]
    return normalized == reversed_text


word = "Level"

if is_palindrome(word):
    print("The string is a palindrome")
else:
    print("The string is not a palindrome")
