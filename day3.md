# Simple Java Project – Day 3

## About
This project focuses on using basic conditional logic and methods in Java.
It helps practice:

- If–else statements
- Simple decision making
- Method usage

This is part of my daily Java practice to strengthen core fundamentals.

---

## Java Code

```java
// Day 3: Check whether a number is even or odd

class NumberCheck {
    void checkEvenOdd(int number) {
        if (number % 2 == 0) {
            System.out.println(number + " is Even");
        } else {
            System.out.println(number + " is Odd");
        }
    }
}

public class Main {
    public static void main(String[] args) {
        NumberCheck obj = new NumberCheck();
        obj.checkEvenOdd(7);
    }
}
