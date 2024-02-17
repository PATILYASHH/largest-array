# Finding the Largest Element in an Array

This C program demonstrates how to find the largest element in an array using a simple linear search algorithm.

## Prerequisites

Make sure you have a C compiler installed on your system. If not, you can download and install one before compiling and running the program.

## How to Compile and Run

1. Open a terminal or command prompt.
2. Navigate to the directory containing the `largest_element.c` file.
3. Compile the program using a C compiler. For example, using GCC:
   ```bash
   gcc largest_element.c -o largest_element
 
1. Run the compiled program:
 ```
./largest_element
 ```
## Program Explanation

- The program starts by initializing an integer array `arr[]` with some numbers.
- It calculates the number of elements in the array `n` using the formula `sizeof(arr) / sizeof(arr[0])`.
- A variable `max` is initialized with the value of the first element of the array (`arr[0]`).
- The program then iterates through the array from the second element (`i = 1`) to find the largest element.
- During each iteration, it checks if the current element is greater than the current maximum value `max`.
- If an element is found to be greater than `max`, `max` is updated with the value of that element.
- Once the loop completes, the program prints the maximum value found in the array using `printf()`.

## Example Output

The largest element in the array is: 20
