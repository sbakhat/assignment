# Python Assignment

Submitted by:
- **Name:** Bhupendra Shah
- **Faculty:** BCSIT - Sec - A
- **Semester:** 2nd
- **College:** KFA 

## Overview
This assignment demonstrates my understanding of Python programming fundamentals through practical implementation. It includes two sets of programs:
- Set A focuses on basic programming concepts like calculations, loops, patterns, and functions
- Set B implements advanced problem-solving techniques using algorithms and data structures

All programs are interactive and include proper error handling and user input validation.

### Set A: Basic Programs
1. Calculator - Does basic math operations
2. Binary Converter - Changes numbers to binary form
3. Age Group Finder - Tells if someone is minor/adult/senior
4. Number Swapper - Swaps two numbers
5. Fibonacci Series - Shows first 10 Fibonacci numbers
6. Prime Checker - Tests if a number is prime
7. Sum Verifier - Checks if two numbers add up to third
8. Factorial Calculator - Finds factorial of a number
9. Division Program - Safely divides numbers
10. Maximum Finder - Finds biggest number in a list
11. Greeting Program - Shows name and age
12. Vowel Counter - Counts vowels in text
13. Multiplication Table - Shows times table
14. Triangle Pattern - Makes star triangle
15. Pyramid Pattern - Makes star pyramid

### Set B: 
1. Palindrome Number - Checks if number reads same both ways
2. Single Number - Finds non-repeated number
3. Two Sum - Finds number pairs that add to target
4. Happy Number - Special number sequence checker
5. Duplicate Finder - Checks for repeated numbers

## How to Run
1. Open `Assignment.ipynb` in Jupyter Notebook
2. Run each cell in order
3. Enter input when asked

## Requirements
- Python 3
- Jupyter Notebook

## File Structure

```
.
├── Assignment.ipynb    # Main Jupyter notebook containing all exercises
├── factorialmodule.py # Custom module for factorial calculation
└── README.md          # This documentation file
```

## Custom Modules

### factorialmodule.py
```python
def factorial(n):
    result = 1
    for i in range(1, n + 1):
        result *= i
    return result
```
- Custom module for factorial calculation
- Used in exercise 8 of Set A

## Usage

1. Make sure you have Python and Jupyter Notebook installed
2. Open `Assignment.ipynb` in Jupyter Notebook
3. Run cells sequentially to see the output
4. Input values when prompted
