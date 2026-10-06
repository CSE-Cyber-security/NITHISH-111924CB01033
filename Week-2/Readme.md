# Week -2: Factorial Calculator

## Problem Statement
Write a Python program to find the factorial of a given number.

## Description
This program calculates the factorial of a non-negative integer. The factorial of a number n (denoted as n!) is the product of all positive integers less than or equal to n.

**Formula:** n! = n × (n-1) × (n-2) × ... × 1

**Special Cases:**
- 0! = 1
- 1! = 1

## Input
```
Enter a number: 5
```

## Output
```
Factorial of 5 = 120
```

## How It Works
1. The program prompts the user to enter a number
2. It validates the input (must be a non-negative integer)
3. It calculates the factorial using an iterative approach
4. It displays the result

## Algorithm
The program uses a simple iterative approach:
- Start with result = 1
- Multiply result by each number from 2 to n
- Return the final result

## Time Complexity
- **Time:** O(n) - Loop runs n-1 times
- **Space:** O(1) - Constant space

## Usage
```bash
python factorial.py
```

Then enter the desired number when prompted.

## Example Test Cases
| Input | Output |
|-------|--------|
| 0 | 1 |
| 1 | 1 |
| 5 | 120 |
| 10 | 3628800 |

## Features
- Input validation
- Error handling for negative numbers
- Clear output format
- Well-documented code with docstrings

## Author
Created as part of Week -2 assignment
