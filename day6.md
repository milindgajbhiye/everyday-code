# Simple Java Project – Day 6

## About
This project demonstrates basic string handling in Java.
It focuses on:

- Working with strings
- Using built-in string methods
- Simple logical checks

This is part of my daily Java practice to strengthen core concepts.

---

## Java Code

```java
// Day 6: Check if a string is empty or not

class StringCheck {
    void checkEmpty(String text) {
        if (text.isEmpty()) {
            System.out.println("The string is empty");
        } else {
            System.out.println("The string is not empty");
        }
    }
}

public class Main {
    public static void main(String[] args) {
        StringCheck obj = new StringCheck();
        obj.checkEmpty("Hello");
    }
}
