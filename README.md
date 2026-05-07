# Matrix Number Analysis Tool (C++)

## Description
A comprehensive C++ application designed for processing 2D data structures and performing number theory analysis. The tool generates a randomized matrix and identifies specific mathematical properties (Prime and Perfect numbers) within the dataset using modular function logic.

## Key Technical Features
* **Modular Code Structure:** Implementation of standalone boolean functions for complex mathematical checks, promoting code reusability.
* **Matrix Manipulation:** Efficient traversal and processing of 2D arrays using nested loops.
* **Algorithmic Complexity:** * **Prime Number Detection:** Optimized primality test logic.
    * **Perfect Number Identification:** Logic for calculating proper divisors and verifying perfect number status.
* **Dynamic Data Handling:** Real-time calculation of maximum values and coordinate-based conditional logic.

## Logic Workflow
1. **Initialization:** Generates a $5 \times 5$ matrix filled with random integers (0-92).
2. **Search & Analysis:** Simultaneously identifies the maximum element and counts prime numbers within the matrix.
3. **Perfect Number Calculation:** If perfect numbers are present, the program calculates their product based on the maximum element's coordinate sum.

## How to Build
1. Requirements: C++ compiler (GCC, Clang, or MSVC).
2. Compilation: `g++ MatrixTool.cpp -o matrix_analyzer`
3. Run: `./matrix_analyzer`

## Learning Objectives
* Implementation of helper functions for cleaner `main()` logic.
* Mastery of 2D array indexing and nested iteration.
* Practical application of number theory in software development.
