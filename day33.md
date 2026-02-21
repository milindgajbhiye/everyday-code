# Simple Python Project – Day 33

## About
This project demonstrates basic string processing in Python.
It focuses on counting how many times a specific character appears in a string.
The goal is to strengthen understanding of loops and conditional logic.

---

## Python Code

```python
# Day 33: Count occurrences of a character in a string

def count_character(text, target):
    count = 0

    for char in text:
        if char == target:
            count += 1

    return count


sample_text = "programming"
character_to_count = "g"

result = count_character(sample_text, character_to_count)

print("Text:", sample_text)
print("Character:", character_to_count)
print("Occurrences:", result)
