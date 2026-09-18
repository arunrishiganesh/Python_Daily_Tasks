# Positive, Negative, or Zero Number Checker

## Description

A simple Python program that identifies whether a given number is **positive, negative, or zero** using conditional statements.

## Concepts Used

* Python Input and Output
* `if`, `elif`, and `else` statements
* Comparison Operators
* Basic Conditional Logic

## How It Works

1. The program accepts a number from the user.
2. It checks whether the number is greater than `0`.
3. If the number is greater than `0`, it is identified as **positive**.
4. If the number is less than `0`, it is identified as **negative**.
5. If neither condition is true, the number is `0`.

## Example

```text
Enter a number: 25
Entered number is positive
```

```text
Enter a number: -10
Entered number is negative
```

```text
Enter a number: 0
no value
```

## Python Code

```python
a = int(input("Enter a number"))

if a > 0:
    print("Entered number is positive")
elif a < 0:
    print("Entered number is negative")
else:
    print("no value")
```

## Purpose

This task helps practice **conditional statements and logical decision-making in Python**.
