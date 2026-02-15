# Simple Python Project – Day 28

## About
This project focuses on basic dictionary operations in Python.
It demonstrates how to iterate through key–value pairs and display stored data.
The goal is to strengthen understanding of dictionaries and loops.

---

## Python Code

```python
# Day 28: Display all key–value pairs in a dictionary

def display_dictionary(data):
    for key, value in data.items():
        print(key, ":", value)


student = {
    "name": "Jordan",
    "age": 21,
    "grade": "A"
}

display_dictionary(student)
