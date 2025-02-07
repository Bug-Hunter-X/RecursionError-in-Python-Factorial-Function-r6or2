# RecursionError in Python Factorial Function

This repository demonstrates a common error in Python: the `RecursionError`.  The `factorial_bug.py` file contains a factorial function that works correctly for positive integers but causes a `RecursionError` when called with a negative integer. The `factorial_solution.py` file provides a solution that handles negative input gracefully.

## Bug Description

The factorial function uses recursion, but lacks error handling for negative input.  When called with a negative number, the recursion continues indefinitely until the maximum recursion depth is exceeded, causing a `RecursionError`.

## Solution

The solution adds an `if` statement to check for negative input, returning an appropriate error message or handling the case as needed.