# Simple Python Project – Day 21

## About
This project demonstrates how to use Python functions with default parameters.
It shows how default values make functions more flexible and easier to use.
The goal is to understand function arguments and improve code readability.

---

## Python Code

```python
# Day 21: Use default parameters in a function

def greet_user(name="User"):
    print("Hello,", name)


greet_user("Alex")
greet_user()
