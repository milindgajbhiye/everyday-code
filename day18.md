# Simple Python Project – Day 18

## About
This project demonstrates basic file handling in Python.
It shows how to write data to a file and then read it back.
The goal is to understand how Python interacts with files in a simple and practical way.

---

## Python Code

```python
# Day 18: Write to a file and read from it

def write_and_read_file():
    file_name = "sample.txt"

    # Writing to the file
    with open(file_name, "w") as file:
        file.write("This is a simple file handling example.\n")
        file.write("Learning Python daily.")

    # Reading from the file
    with open(file_name, "r") as file:
        content = file.read()

    print("File Content:")
    print(content)


write_and_read_file()
