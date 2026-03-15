# Simple Python Project – Day 52

## About
This project focuses on basic string processing and counting logic in Python.
It demonstrates how to count the number of spaces in a sentence.
The goal is to practice string traversal and simple character analysis using loops.

---

## Python Code

```python
# Day 52: Count spaces in a sentence

def count_spaces(text):
    space_count = 0

    for char in text:
        if char == " ":
            space_count += 1

    return space_count


sentence = "Python practice makes coding better"
result = count_spaces(sentence)

print("Sentence:", sentence)
print("Number of spaces:", result)
