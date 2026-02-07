# Simple Python Project – Day 24

## About
This project focuses on using loops with conditional logic to build a simple pattern.
It demonstrates how nested logic and iteration can be used together to produce structured output.
The goal is to improve control over loops and understand step-by-step execution.

---

## Python Code

```python
# Day 24: Print a simple star pattern

def print_pattern(rows):
    for i in range(1, rows + 1):
        print("*" * i)


print_pattern(5)
