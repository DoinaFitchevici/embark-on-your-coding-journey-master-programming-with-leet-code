# Assignment 3: Implementing Basic Algorithms

## Objective

Understand and implement basic algorithms to solidify comprehension.

## Expected Capabilities

- Identify algorithm types
- Implement basic sorting and search algorithms
- Analyze algorithm complexity

## Instructions

### Part 1

**Implement Bubble Sort**

Write a function to sort an array using the Bubble Sort algorithm.

```
void bubbleSort(int[] arr) {
    int n = arr.length;
    for (int i = 0; i < n-1; i++)
        for (int j = 0; j < n-i-1; j++)
            if (arr[j] > arr[j+1]) {
                // swap arr[j] and arr[j+1]
                int temp = arr[j];
                arr[j] = arr[j+1];
                arr[j+1] = temp;
            }
}
```

**Implement Binary Search**

Write a function to find an element in a sorted array using the Binary Search algorithm.

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

## Tasks

### Task 1: Implement Bubble Sort

Develop a program with Bubble Sort to understand how sorting works.

```
void bubbleSort(int[] arr) {...}
```

### Task 2: Implement Binary Search

Create a Binary Search implementation on a sample dataset and evaluate its effectiveness compared to linear search.

```
int binarySearch(int[] arr, int x) {...}
```

## Submission Instructions

Submit the completed programs with screenshots of the output in a text file.

## Checklist

- [ ] Bubble Sort implemented and working
- [ ] Binary Search implemented and working
- [ ] Complexity analysis included

## Check for Understanding

**What is the main advantage of using Binary Search over Linear Search?**

- Faster search time for unsorted arrays
- Works with any data type
- Faster search time for sorted arrays

**Answer:** [Your answer here]

**Bubble Sort is an example of which type of algorithm?**

- Divide and conquer
- Greedy
- Sorting

**Answer:** [Your answer here]

**What does space complexity refer to?**

- Amount of memory required
- Time taken to execute
- Length of the code

**Answer:** [Your answer here]