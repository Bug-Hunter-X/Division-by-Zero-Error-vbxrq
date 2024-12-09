# Division by Zero Error in C
This example demonstrates a common runtime error in C: division by zero.  The program attempts to divide an integer by zero, which leads to undefined behavior and typically a program crash (segmentation fault).

## Bug Description:
The `main` function attempts to divide the integer variable `a` by the integer variable `b`, where `b` is initialized to 0. This results in a division-by-zero error.

## Solution:
The solution involves adding a check to ensure that the denominator is not zero before performing the division.  If the denominator is zero, an appropriate error message is printed, or alternative actions are taken to prevent the crash. 