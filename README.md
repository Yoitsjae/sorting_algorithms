# Sorting Algorithms

This project implements several sorting algorithms in C. Sorting algorithms are fundamental in computer science and are used to arrange data in a specific order. In this project, we've implemented the following sorting algorithms:

1. Bubble Sort
2. Insertion Sort
3. Selection Sort
4. Quick Sort

Each algorithm is implemented in a separate C file and can be used to sort arrays of integers. Additionally, we've provided Big O notations for the time complexity of each algorithm in the `0-O`, `1-O`, `2-O`, and `3-O` files.

## Table of Contents

- [Usage](#usage)
- [Algorithms Implemented](#algorithms-implemented)
- [Compilation](#compilation)
- [Running Tests](#running-tests)
- [Contributing](#contributing)
- [License](#license)

## Usage

To use these sorting algorithms, you can include the respective C file in your project and call the sorting functions with your data. Below are the algorithms implemented and their corresponding C files:

- Bubble Sort: `0-bubble_sort.c`
- Insertion Sort: `1-insertion_sort_list.c`
- Selection Sort: `2-selection_sort.c`
- Quick Sort: `3-quick_sort.c`

You can find example test programs in the `main` files with each algorithm implementation.

## Algorithms Implemented

### 1. Bubble Sort

Bubble Sort is a simple sorting algorithm that repeatedly steps through the list, compares adjacent elements, and swaps them if they are in the wrong order. The pass through the list is repeated until no swaps are needed, which indicates that the list is sorted.

### 2. Insertion Sort

Insertion Sort is another simple sorting algorithm that builds the final sorted array one item at a time. It is much less efficient on large lists than more advanced algorithms such as quicksort, heapsort, or merge sort.

### 3. Selection Sort

Selection Sort is an in-place comparison-based sorting algorithm. It works by dividing the input list into two parts: a sorted sublist of items that is built up from left to right at the front of the list and a sublist of the remaining unsorted items.

### 4. Quick Sort

Quick Sort is a divide-and-conquer sorting algorithm. It works by selecting a 'pivot' element from the array and partitioning the other elements into two sub-arrays, according to whether they are less than or greater than the pivot.

## Compilation

All the sorting algorithms are written in C and can be compiled on an Ubuntu 20.04 LTS system using `gcc`. You can use the provided compilation commands in the `main` files, for example:

```bash
gcc -Wall -Wextra -Werror -pedantic -std=gnu89 0-bubble_sort.c 0-main.c print_array.c -o bubble
```

Make sure you have the required development tools installed on your system.

## Running Tests

You can run test programs provided in the `main` files to see the sorting algorithms in action. After compilation, execute the test program, for example:

```bash
./bubble
```

Each algorithm's test program will demonstrate how the sorting algorithm works on a sample array.

## Contributing

If you would like to contribute to this project, please follow these steps:

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Create a new Pull Request
