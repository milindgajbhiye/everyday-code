# Simple Java Project – Day 7

## About
This project focuses on using arrays and loops together to perform a simple operation.
It demonstrates:

- Traversing an array
- Counting elements
- Basic conditional logic

This is part of my daily Java practice to strengthen core Java and DSA fundamentals.

---

## Java Code

```java
// Day 7: Count even numbers in an array

class EvenCounter {
    int countEvenNumbers(int[] numbers) {
        int count = 0;

        for (int i = 0; i < numbers.length; i++) {
            if (numbers[i] % 2 == 0) {
                count++;
            }
        }

        return count;
    }
}

public class Main {
    public static void main(String[] args) {
        int[] values = {2, 5, 8, 11, 14};

        EvenCounter obj = new EvenCounter();
        int result = obj.countEvenNumbers(values);

        System.out.println("Number of even elements: " + result);
    }
}
