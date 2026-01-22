# Simple Python Project – Day 12

## About
This project focuses on working with dictionaries in Python.
It demonstrates how to store data in key–value pairs and access that data using simple logic.
The goal is to understand how dictionaries help organize and manage related information.

---

## Python Code

```python
# Day 12: Store and display student details using a dictionary

def display_student_details(student):
    print("Student Details:")
    print("Name:", student["name"])
    print("Age:", student["age"])
    print("Course:", student["course"])


student_info = {
    "name": "Alex",
    "age": 20,
    "course": "Computer Science"
}

display_student_details(student_info)
