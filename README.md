# Dynamic Array Operations in C++

## Overview
This C++ program demonstrates the use of pointers and dynamic arrays by implementing three core functions:
1. **generate** - Creates a dynamic array of random integers.
2. **duplicate** - Duplicates the contents of a given dynamic array.
3. **display** - Displays the contents of a dynamic array with formatted output.

## Features
- Uses **dynamic memory allocation** to manage arrays.
- Implements **random number generation** for array initialization.
- Demonstrates **pointer operations** for array manipulation.

## Functions
### `int* generate(unsigned int n)`
Generates a dynamic array of `n` random integers (0-99) and returns a pointer to the array.

### `int* duplicate(int* arr, unsigned int size)`
Creates a new dynamic array with each element duplicated (e.g., `[1,2,3]` → `[1,1,2,2,3,3]`).

### `void display(int* arr, unsigned int size)`
Displays the array elements, printing **8 elements per line** for better readability.

## Usage
1. Compile the program using a C++ compiler (e.g., g++):
   ```sh
   g++ -o dynamic_array main.cpp
   ```
2. Run the program:
   ```sh
   ./dynamic_array
   ```
3. Enter the desired array size and observe the output.

## Memory Management
- The program ensures proper **memory deallocation** using `delete[]` to prevent memory leaks.

## Example Output
```
Enter the size of the dynamic array: 5
Original array:
12 45 78 23 56

Duplicated array:
12 12 45 45 78 78 23 23 56 56
```

## Dependencies
- C++ standard library (`cstdlib`, `ctime`, `iostream`)

## Author
Developed for demonstrating pointers and dynamic arrays in C++.

