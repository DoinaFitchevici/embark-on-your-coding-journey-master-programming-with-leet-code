# Fundamental Data Structures

## Overview

Delve into fundamental data structures like arrays, strings, and linked lists. Experience hands-on learning by tackling basic problems on Leet Code.

## Learning Objectives

- Recognize and implement essential data structures for problem-solving
- Analyze and compare time and space complexities of data structures
- Demonstrate proficiency in manipulating arrays, strings, and linked lists
- Choose appropriate data structures for specific problem contexts

## Topics Covered

- Arrays
- Strings
- Linked lists

## Status

complete

## Subsections

### Introduction to Arrays

Arrays are the simplest and most widely used data structures. An array is a collection of items stored at contiguous memory locations. The idea is to store multiple items of the same type together. This helps to calculate the position of each element by simply adding an offset to a base value.

**Video URL:** http://video.com/introToArrays

**Code Examples:**

```
int[] numbers = {1, 2, 3, 4, 5};
```

```
String[] names = {"Alice", "Bob", "Charlie"};
```

```
int[][] matrix = {{1, 2, 3}, {4, 5, 6}, {7, 8, 9}};
```

```
int[] numbers = new int[10]; // array with size 10
```

```
int[] sortedNumbers = Arrays.sort(numbers); // sorting array
```

**External Links:**

- [https://www.geeksforgeeks.org/arrays-in-java/](https://www.geeksforgeeks.org/arrays-in-java/)
- [test](test)

**Quizzes:**

**What is the starting index of an array in Java?**

- 0
- 1
- Depends on the array

**Answer:** 0

**What is the correct way to declare a 2D array in Java?**

- int[][] arr;
- int[] arr[];
- Both

**Answer:** Both

### Understanding Array Operations

Performing operations on arrays is fundamental. These operations include accessing, updating, and iterating through the elements. Operations are often tested in coding interviews and assessments.

**Video URL:** http://video.com/arrayOperations

**Code Examples:**

```
int[] numbers = {1, 2, 3}; numbers[0] = 4; // update first element
```

```
int index = Arrays.binarySearch(numbers, 3); // searching for element 3
```

```
int[] copied = Arrays.copyOf(numbers, 5); // copying array
```

```
Arrays.sort(numbers); // sorting array
```

```
Arrays.equals(numbers, copied); // comparing arrays
```

**External Links:**

- [https://www.w3schools.com/java/java_arrays.asp](https://www.w3schools.com/java/java_arrays.asp)

**Quizzes:**

**How do you access the third element of an array named 'arr'?**

- arr[2]
- arr[3]
- arr[1]

**Answer:** arr[2]

### Introduction to Linked Lists

Linked lists are linear data structures where elements are not stored at contiguous memory locations. Each element points to the next, forming a chain-like structure. They are crucial for operations that involve frequent insertions and deletions.

**Video URL:** http://video.com/introToLinkedLists

**Code Examples:**

```
class Node { int data; Node next; Node(int d) { data = d; } }
```

```
// Traverse a linked list
Node current = head;
while (current != null) {
    System.out.println(current.data);
    current = current.next;
}
```

```
// Reverse a linked list
Node previous = null;
Node current = head;
while (current != null) {
    Node next = current.next;
    current.next = previous;
    previous = current;
    current = next;
}
head = previous;
```

```
// Sort a linked list
// This is a complex operation and may require converting to an array and sorting
```

**External Links:**

- [https://www.javatpoint.com/ds-linked-list](https://www.javatpoint.com/ds-linked-list)
- [https://www.geeksforgeeks.org/data-structure-linked-list/](https://www.geeksforgeeks.org/data-structure-linked-list/)
- [https://www.tutorialspoint.com/data_structures_algorithms/linked_list_algorithms.htm](https://www.tutorialspoint.com/data_structures_algorithms/linked_list_algorithms.htm)

**Quizzes:**

**What makes linked lists different from arrays?**

- Elements are stored sequentially
- Elements point to the next forming chains
- They cannot store large data

**Answer:** Elements point to the next forming chains

**Name a fundamental operation unique to linked lists compared to arrays.**

- Traversal from head to tail
- Random access
- Index-based access

**Answer:** Traversal from head to tail

## Supplemental Videos

- [http://video.com/deepDiveLinkedLists](http://video.com/deepDiveLinkedLists)

## References

- [https://www.geeksforgeeks.org/data-structures/](https://www.geeksforgeeks.org/data-structures/)

## Podcast URL

No podcast available