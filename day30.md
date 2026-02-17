# Simple Python Project – Day 30

## About
This project focuses on basic string analysis and conditional logic in Python.
It demonstrates how to count the number of words in a sentence.
The goal is to practice string operations and simple data processing.

---

## Python Code

```python
# Day 30: Count words in a sentence

def count_words(sentence):
    words = sentence.split()
    return len(words)


text = "Practicing Python projects every single day"
result = count_words(text)

print("Sentence:", text)
print("Word count:", result)
