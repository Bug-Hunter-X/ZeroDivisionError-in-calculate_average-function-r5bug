# Python Code Bug: ZeroDivisionError in Average Calculation

This repository demonstrates a common Python code error: a `ZeroDivisionError` that occurs when calculating the average of an empty list or a list with all zero values.

The `bug.py` file contains the erroneous code.  The `bugSolution.py` provides the corrected version with improved error handling.

## How to reproduce the bug:
1. Clone the repository.
2. Run `bug.py` using a Python interpreter.
3. Observe the `ZeroDivisionError` when an empty list or a list with all zeros is passed to the function.

## Solution:
The solution is to add explicit error handling to check for empty or all-zero lists before performing the division.