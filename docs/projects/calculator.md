# Calculator Application

A Java-based calculator application that performs basic arithmetic operations.

## Features

- Addition
- Subtraction
- Multiplication
- Division
- Clear functionality
- Error handling for invalid inputs

## Code Structure

```java
public class Calculator {
    public double add(double a, double b) {
        return a + b;
    }

    public double subtract(double a, double b) {
        return a - b;
    }

    public double multiply(double a, double b) {
        return a * b;
    }

    public double divide(double a, double b) {
        if (b == 0) {
            throw new ArithmeticException("Division by zero!");
        }
        return a / b;
    }
}
```

## How to Use

1. Import the Calculator class
2. Create a new Calculator instance
3. Call the desired method with appropriate parameters

Example:
```java
Calculator calc = new Calculator();
double result = calc.add(5, 3); // returns 8
```