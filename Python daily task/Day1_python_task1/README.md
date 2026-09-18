# Even or Odd Number Checker

## Description

A simple Python program that determines whether a given number is **even or odd** using the modulus (`%`) operator and conditional statements.

## Concepts Used

* Python Input and Output
* `if-else` Conditional Statements
* Modulus (`%`) Operator
* Basic Arithmetic Operations

## How It Works

1. The program asks the user to enter a number.
2. It checks whether the number is divisible by `2`.
3. If the remainder is `0`, the number is **even**.
4. Otherwise, the number is **odd**.

## Example

```text
Enter a number: 10
The number is even
```

```text
Enter a number: 7
The number is odd
```

## Python Code

```python
a = int(input("Enter a number"))

if a % 2 == 0:
    print("The number is even")
else:
    print("The number is odd")
```
