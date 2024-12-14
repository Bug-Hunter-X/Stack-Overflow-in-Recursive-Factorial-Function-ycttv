# Haskell Factorial Bug

This repository demonstrates a common error in recursive Haskell functions: improper handling of negative inputs leading to stack overflow. The `factorialBug.hs` file contains the buggy code, while `factorialSolution.hs` provides a corrected version.

## Bug Description
The original `factorial` function lacks input validation, resulting in infinite recursion when called with a negative number. This leads to a stack overflow exception.  The solution adds a check to handle negative inputs appropriately.

## Solution
The corrected function adds a check to explicitly handle negative inputs, returning an error value or raising an exception instead of causing infinite recursion.