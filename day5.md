# Simple Java Project – Day 5

## About
This project focuses on using loops to perform repeated operations in Java.
It demonstrates:

- `for` loop usage
- Counting logic
- Method execution

This is part of my daily Java practice to build strong fundamentals.

---

## Java Code

```java
// Day 5: Print numbers from 1 to N using a loop

class NumberPrinter {
    void printNumbers(int n) {
        for (int i = 1; i <= n; i++) {
            System.out.println(i);
        }
    }
}

public class Main {
    public static void main(String[] args) {
        NumberPrinter obj = new NumberPrinter();
        obj.printNumbers(5);
    }
}
