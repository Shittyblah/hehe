## Table of Contents

- [Introduction](#introduction)
- [Armstrong Number Algorithm](#armstrong-number-algorithm)
- [Code Implementation](#code-implementation)
  - [Input](#input)
  - [Looping](#looping)
  - [Armstrong Number Check](#armstrong-number-check)
  - [Output](#output)
- [Example Usage](#example-usage)

## Introduction

This program finds and prints Armstrong numbers within a specified range. An Armstrong number is a positive integer such that the sum of its digits raised to the power of the number of digits is equal to the number itself.

## Armstrong Number Algorithm

The algorithm for finding Armstrong numbers is as follows:

1. Convert the number to a string.
2. Find the number of digits in the number.
3. Create a temporary variable to store the original number.
4. Loop through the number.
5. In each iteration, extract the last digit of the number and raise it to the power of the number of digits.
6. Add the result to the sum.
7. Remove the last digit from the number.
8. Repeat steps 5-7 until the number becomes 0.
9. If the sum is equal to the original number, then the number is an Armstrong number.

## Code Implementation

### Input

The program takes two positive integer inputs:

- `lowNumber`: The lower bound of the range.
- `highNumber`: The upper bound of the range.

### Looping

The program loops through all the integers in the range `[lowNumber, highNumber]`.

### Armstrong Number Check

For each integer `i` in the range, the program checks if it is an Armstrong number using the algorithm described above.

### Output

If `i` is an Armstrong number, it is printed to the console.

## Example Usage

The following is an example of how to use the program:

```
Enter a positive low integer value: 1
Enter a positive high integer value: 1000

Armstrong Numbers:
1
153
370
371
407
```