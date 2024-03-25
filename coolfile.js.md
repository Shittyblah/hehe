**## Table of Contents**

- [Introduction](#introduction)
- [Armstrong Number Algorithm](#armstrong-number-algorithm)
- [Code Implementation](#code-implementation)
  - [Input](#input)
  - [Looping](#looping)
  - [Armstrong Number Check](#armstrong-number-check)
  - [Output](#output)
- [Example Usage](#example-usage)

**## Introduction**

This program identifies and displays Armstrong numbers within a specified range. An Armstrong number is a positive integer whose digits, when raised to the power of the number of digits, sum up to the number itself.

**## Armstrong Number Algorithm**

The Armstrong number algorithm involves the following steps:

1. Convert the number to a string.
2. Determine the number of digits in the number.
3. Store the original number in a temporary variable.
4. Iterate through the number.
5. In each iteration:
   - Extract the last digit of the number.
   - Raise the last digit to the power of the number of digits.
   - Add the result to a sum.
   - Remove the last digit from the number.
6. Repeat steps 5 until the number becomes 0.
7. If the sum is equal to the original number, then the number is an Armstrong number.

**## Code Implementation**

### Input

The program prompts the user for two positive integer inputs:

- `lowNumber`: The lower bound of the range.
- `highNumber`: The upper bound of the range.

### Looping

The program iterates through all the integers in the range `[lowNumber, highNumber]`.

### Armstrong Number Check

For each integer `i` in the range, the program checks if it is an Armstrong number using the algorithm described above.

### Output

If `i` is an Armstrong number, it is printed to the console.

**## Example Usage**

Here is an example of how to use the program:

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