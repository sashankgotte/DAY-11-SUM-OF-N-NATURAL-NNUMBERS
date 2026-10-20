# Day 11 - Sum of N Natural Numbers 🐍

## 📌 Description
This Python program calculates the sum of the first N natural numbers using a `for` loop.

The user enters a number `N`, and the program adds all natural numbers from 1 to N and displays the total.

## 💻 Code
```python
n = int(input("Enter N: "))

total = 0

for i in range(1, n + 1):
    total += i

print("Sum =", total)
```

## ▶️ Example Output
```text
Enter N: 5
Sum = 15
```

## 🧠 Concepts Learned
- User input using `input()`
- Type conversion using `int()`
- `for` loop
- `range()` function
- Accumulator variable
- Addition using `+=`

## 🎯 Objective
To understand how loops can be used to calculate the sum of natural numbers.

## 📅 Challenge
**100 Days of Python Coding Challenge – Day 11**

## 👨‍💻 Language
Python 🐍