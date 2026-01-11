# Simple Java Project – Day 2

## About
This project continues my daily Java practice.
It demonstrates the use of:

- Arrays (basic Data Structure)
- Loops
- Simple method design

The purpose is to apply fundamental DSA and Java concepts through small, consistent projects.

---

## Java Code

```java
// Day 2: Find the sum of elements in an array

class ArraySum {
    int calculateSum(int[] numbers) {
        int sum = 0;

        for (int i = 0; i < numbers.length; i++) {
            sum = sum + numbers[i];
        }

        return sum;
    }
}

public class Main {
    public static void main(String[] args) {
        int[] values = {10, 20, 30, 40};

        ArraySum obj = new ArraySum();
        int result = obj.calculateSum(values);

        System.out.println("Sum of array elements: " + result);
    }
}
