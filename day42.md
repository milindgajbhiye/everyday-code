# Simple Python Project – Day 42

## About
This project demonstrates basic string processing in Python.
It focuses on counting the number of uppercase and lowercase letters in a sentence.
The goal is to practice string traversal and conditional checks while understanding how characters can be analyzed.

---

## Python Code

```python
# Day 42: Count uppercase and lowercase letters in a string

def count_case(text):
    upper_count = 0
    lower_count = 0

    for char in text:
        if char.isupper():
            upper_count += 1
        elif char.islower():
            lower_count += 1

    return upper_count, lower_count


sample_text = "Learning Python Every Day"
upper, lower = count_case(sample_text)

print("Text:", sample_text)
print("Uppercase letters:", upper)
print("Lowercase letters:", lower)
