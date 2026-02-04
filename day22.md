# Simple Python Project – Day 22

## About
This project focuses on working with tuples in Python.
It demonstrates how tuples store ordered data and how they can be accessed using indexing.
The goal is to understand when to use tuples instead of lists.

---

## Python Code

```python
# Day 22: Access elements from a tuple

def display_coordinates(point):
    print("X coordinate:", point[0])
    print("Y coordinate:", point[1])


coordinates = (10, 20)
display_coordinates(coordinates)
