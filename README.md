# Digit Sum and Product Checker in C

A simple C programming project that extracts the digits of an integer, calculates their sum and product, and compares the two results.

## Description

This program performs the following operations:

1. **Digit Extraction:** Extracts each digit using the modulus operator (`%`).
2. **Sum Calculation:** Adds all the digits together.
3. **Product Calculation:** Multiplies all the digits together.
4. **Comparison:** Checks whether the sum and product are equal.

If both results are equal, the program prints `YES`. Otherwise, it prints `No`.

## Example 1

**Input:**
```text
Enter a number: 123
```

**Calculation:**

- Sum = 1 + 2 + 3 = 6
- Product = 1 × 2 × 3 = 6

**Output:**
```text
YES
```

## Example 2

**Input:**
```text
Enter a number: 234
```

**Calculation:**

- Sum = 2 + 3 + 4 = 9
- Product = 2 × 3 × 4 = 24

**Output:**
```text
No
```

## Technologies Used

- C Programming Language
- Standard Input/Output (`stdio.h`)

## Concepts Practiced

| Concept | Application |
|---|---|
| Variables | Storing sum, product, and digits |
| While Loop | Processing each digit |
| Modulus (`%`) | Extracting the last digit |
| Integer Division (`/`) | Removing the last digit |
| Arithmetic Operations | Calculating sum and product |
| If-Else | Comparing the two results |

## How to Compile and Run

### Compile
```bash
gcc main.c -o luckynumber
```

### Run on Windows
```bash
luckynumber.exe
```

### Run on Linux / macOS
```bash
./luckynumber
```





## Author

**Achraf Djelid**

