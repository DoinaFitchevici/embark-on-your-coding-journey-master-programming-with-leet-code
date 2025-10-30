# Introduction to Algorithms

## Overview

Get introduced to basic algorithms such as sorting and searching. Utilize these algorithms to address more complex challenges on Leet Code.

## Learning Objectives

- Identify suitable algorithms for various problem-solving scenarios
- Understand algorithm efficiency and performance trade-offs
- Adapt and implement algorithms for optimized solutions
- Enhance problem-solving skills through algorithm application

## Topics Covered

- Searching algorithms
- Sorting algorithms

## Status

complete

## Subsections

### Understanding Algorithms

An algorithm is a step-by-step procedure or formula for solving a problem. Algorithms include everything from recipes to complex math operations. They are essentially a set of precise instructions that should lead to a concrete result.

**Video URL:** https://edu.video.com/understandingAlgorithms

**Code Examples:**

No code examples available

**External Links:**

- [https://www.khanacademy.org/computing/computer-science/algorithms](https://www.khanacademy.org/computing/computer-science/algorithms)

**Quizzes:**

**What is an algorithm?**

- A precise set of rules for solving a specific problem
- A computer program
- A hardware component

**Answer:** A precise set of rules for solving a specific problem

### Algorithm Complexity

The complexity of an algorithm is a measure of the amount of time and/or space resources required by an algorithm to run, as a function of the length of the input. Two main types of complexities are Time complexity and Space complexity.

**Video URL:** https://edu.video.com/algorithmComplexity

**Code Examples:**

No code examples available

**External Links:**

- [https://bigocheatsheet.com](https://bigocheatsheet.com)

**Quizzes:**

**What does time complexity measure?**

- Memory usage
- Execution time
- Number of lines of code

**Answer:** Execution time

### Basic Algorithm Types

Basic types of algorithms include:
- Sorting algorithms (e.g., Bubble Sort, Merge Sort)
- Search algorithms (e.g., Binary Search, Linear Search)
- Recursive algorithms that call themselves and solve problems by breaking them into simpler sub-problems

**Video URL:** https://edu.video.com/basicAlgorithmTypes

**Code Examples:**

```
int binarySearch(int[] arr, int key) {
   int low = 0;
   int high = arr.length - 1;
   while (low <= high) {
      int middle = (low + high) / 2;
      if (arr[middle] < key) {
         low = middle + 1;
      } else if (arr[middle] > key) {
         high = middle - 1;
      } else {
         return middle;
      }
   }
   return -1;
}
```

**External Links:**

- [https://www.geeksforgeeks.org/sorting-algorithms](https://www.geeksforgeeks.org/sorting-algorithms)

**Quizzes:**

**Which type of algorithm is Merge Sort?**

- Search algorithm
- Sorting algorithm
- Graph algorithm

**Answer:** Sorting algorithm

## Supplemental Videos

- [https://edu.video.com/introToAlgo](https://edu.video.com/introToAlgo)

## References

- [https://www.geeksforgeeks.org/algorithms](https://www.geeksforgeeks.org/algorithms)
- [https://www.tutorialspoint.com/data_structures_algorithms](https://www.tutorialspoint.com/data_structures_algorithms)

## Podcast URL

No podcast available