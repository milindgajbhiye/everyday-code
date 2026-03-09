# Simple Python Project – Day 47

## About
This project demonstrates how to work with dictionaries and basic counting logic in Python.
It shows how to count the frequency of elements in a list.
The goal is to understand how dictionaries can store and track occurrences of data.

---

## Python Code

```python
# Day 47: Count frequency of elements in a list

def count_frequency(items):
    frequency = {}

    for item in items:
        if item in frequency:
            frequency[item] += 1
        else:
            frequency[item] = 1

    return frequency


values = ["apple", "banana", "apple", "orange", "banana", "apple"]
result = count_frequency(values)

print("Items:", values)
print("Frequency:", result)
