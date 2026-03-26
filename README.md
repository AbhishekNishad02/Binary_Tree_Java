# Binary_Tree_Java
# Binary Tree Implementation in Java

## Overview

This project provides an implementation of a Binary Tree in Java, covering fundamental operations and traversal techniques commonly used in data structures.

---

## Features

The following functionalities are included:

* Preorder Traversal (Root → Left → Right)
* Inorder Traversal (Left → Root → Right)
* Postorder Traversal (Left → Right → Root)
* Level Order Traversal (Breadth-First Search)
* Depth-First Search (DFS)
* Breadth-First Search (BFS)
* Size of the Tree (Total number of nodes)
* Sum of all node values
* Product of all node values

---

## Binary Tree Structure

A Binary Tree is a hierarchical data structure in which each node has at most two children:

* Left child
* Right child

---

## Traversal Methods

### Preorder Traversal

Processes the current node before its child nodes:
Root → Left → Right

### Inorder Traversal

Processes the left subtree, then the current node, followed by the right subtree:
Left → Root → Right

### Postorder Traversal

Processes the child nodes before the current node:
Left → Right → Root

---

## BFS and DFS

### Breadth-First Search (BFS)

* Traverses nodes level by level
* Implemented using a queue
* Also known as level order traversal

### Depth-First Search (DFS)

* Traverses as deep as possible before backtracking
* Implemented using recursion or a stack
* Includes preorder, inorder, and postorder traversals

---

## Core Operations

### Size of the Tree

Returns the total number of nodes in the tree.

### Sum of Node Values

Calculates the sum of all node values.

### Product of Node Values

Calculates the product of all node values.

---

## Example

Given the following tree:

```
    1
   / \
  2   3
 / \
4   5
```

Expected outputs:

* Preorder: 1 2 4 5 3
* Inorder: 4 2 5 1 3
* Postorder: 4 5 2 3 1
* Level Order: 1 2 3 4 5
* Size: 5
* Sum: 15
* Product: 120

---

## How to Run

1. Compile the program:
   javac Main.java

2. Execute the program:
   java Main

---

## Technologies Used

* Java
* Core Data Structures

---

## Conclusion

This implementation demonstrates essential Binary Tree operations and serves as a foundational reference for learning tree-based algorithms and recursive problem-solving.
