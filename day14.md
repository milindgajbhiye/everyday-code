# Simple Python Project – Day 14

## About
This project focuses on using functions and loops to perform a simple counting operation.
It demonstrates how to work with lists and apply conditions to count specific elements.
The goal is to improve logical thinking and reinforce Python fundamentals through small, clear examples.

---

## Python Code

```python
# Day 14: Count occurrences of a specific element in a list

def count_occurrences(items, target):
    count = 0

    for item in items:
        if item == target:
            count += 1

    return count


values = ["apple", "banana", "apple", "orange", "apple"]
target_item = "apple"

result = count_occurrences(values, target_item)

print("Item to count:", target_item)
print("Number of occurrences:", result)
