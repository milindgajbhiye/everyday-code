# Simple Python Project – Day 50

## About
This project demonstrates a basic use of Python dictionaries and conditional logic.
It shows how to check whether a key exists in a dictionary before accessing its value.
The goal is to practice safe data access and dictionary operations.

---

## Python Code

```python
# Day 50: Check if a key exists in a dictionary

def check_key(data, key):
    if key in data:
        print("Key found. Value:", data[key])
    else:
        print("Key not found in dictionary")


student = {
    "name": "Jordan",
    "age": 22,
    "course": "Computer Science"
}

check_key(student, "age")
check_key(student, "grade")
