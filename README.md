# C Leap Year Checker

## Explanation

This program checks whether a given year is a leap year.

A leap year is generally divisible by 4 but years divisible by 100 are not leap years unless they are also divisible by 400.

## Problem Statement

Write a C program to read a year and determine whether it is a leap year.

## Features

- Accepts a year
- Checks leap year conditions
- Uses modulus operator
- Uses logical operators
- Displays the result

## How It Works

The program accepts a year from the user.

A year is a leap year if:

The year is divisible by 400

OR

The year is divisible by 4 and not divisible by 100.

The program checks these conditions using the modulus operator and logical operators.

## Technologies Used

- C
- GCC Compiler
- Code Editor

## Data Structure Used

No data structure is used.

## Methods Used

- main()
- printf()
- scanf()

## Operators Used

- % Modulus
- == Equality
- != Not equal
- && Logical AND
- || Logical OR

## Program Flow

Start
↓
Read year
↓
Check divisibility by 400
↓
OR check divisibility by 4
↓
Check not divisible by 100
↓
If condition is true
↓
Display Leap Year
↓
Otherwise
↓
Display Not a Leap Year
↓
End

## Sample Input

Enter a year: 2024

## Sample Output

2024 is a leap year.

## Sample Input 2

Enter a year: 2023

## Sample Output 2

2023 is not a leap year.

## Time Complexity

O(1)

## Space Complexity

O(1)

## Key Learning

This program teaches how to combine arithmetic and logical operators to implement multiple conditions in C.

## File Location

leap_year.c

## Repository Structure

C-Leap-Year-Checker/
├── README.md
└── leap_year.c

## Author

V.Harini
