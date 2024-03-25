## Table of Contents
- Overview
- Implementation
  - Input
  - Armstrong Number Check
  - Output

## Overview
This program finds and prints all Armstrong numbers within a specified range. An Armstrong number is a positive integer such that the sum of its digits raised to the power of the number of digits is equal to the number itself.

## Implementation
### Input
The program takes two positive integer inputs:

- `lowNumber`: The lower bound of the range to search for Armstrong numbers.
- `highNumber`: The upper bound of the range to search for Armstrong numbers.

### Armstrong Number Check
For each number `i` in the range `[lowNumber, highNumber]`, the program performs the following steps to check if `i` is an Armstrong number:

1. Convert `i` to a string and determine the number of digits `numberOfDigits`.
2. Initialize a sum variable `sum` to 0.
3. Create a temporary variable `temp` and set it equal to `i`.
4. While `temp` is greater than 0:
    - Calculate the remainder of `temp` divided by 10 and store it in `remainder`.
    - Add `remainder` raised to the power of `numberOfDigits` to `sum`.
    - Remove the last digit from `temp` by dividing it by 10 and converting the result to an integer.
5. If `sum` is equal to `i`, then `i` is an Armstrong number and it is printed to the console.

### Output
The program prints all Armstrong numbers found within the specified range to the console.