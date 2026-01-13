# Simple Java Project – Day 4

## About
This project demonstrates how to work with user-defined methods and return values in Java.
It focuses on:

- Method creation
- Returning values
- Basic arithmetic logic

This is part of my daily Java practice to strengthen core programming concepts.

---

## Java Code

```java
// Day 4: Find the maximum of two numbers

class MaximumFinder {
    int findMax(int a, int b) {
        if (a > b) {
            return a;
        } else {
            return b;
        }
    }
}

public class Main {
    public static void main(String[] args) {
        MaximumFinder obj = new MaximumFinder();

        int num1 = 25;
        int num2 = 40;

        int max = obj.findMax(num1, num2);
        System.out.println("Maximum number is: " + max);
    }
}
