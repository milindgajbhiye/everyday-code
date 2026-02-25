# Simple Python Project – Day 36

## About
This project focuses on basic string manipulation and function usage in Python.
It demonstrates how to convert a string into uppercase without using complex logic.
The goal is to reinforce understanding of built-in string methods and clean code structure.

---

## Python Code

```python
# Day 36: Convert a string to uppercase

def convert_to_uppercase(text):
    return text.upper()


sample_text = "daily python practice"
result = convert_to_uppercase(sample_text)

print("Original text:", sample_text)
print("Uppercase text:", result)
