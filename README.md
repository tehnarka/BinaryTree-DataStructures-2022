# Binary Tree and Data Structures

**Description:**
This project demonstrates the implementation of fundamental data structures, including stacks, queues, and binary trees. It features a Binary Search Tree (BST) with methods for insertion, traversal (infix, breadth-first), and searching, showcasing object-oriented programming principles.

---

## Objectives

1. **Implement Core Data Structures:**
   - Stack (LIFO operations)
   - Queue (FIFO operations)
   - Binary Tree and Binary Search Tree (BST)

2. **Provide Core Functionalities:**
   - Binary Tree traversals (infix, breadth-first).
   - BST operations: insertion, searching, and finding minimum/maximum values.
   - Stack and Queue push, pop, and print methods.

3. **Encourage Object-Oriented Programming Practices:**
   - Use of classes for data structures.
   - Modular and reusable code.

---

## Features

1. **Stack Implementation:**
   - Attributes: `size`, `items`.
   - Methods: `push`, `pop`, `print`.

2. **Queue Implementation:**
   - Attributes: `size`, `items`.
   - Methods: `push`, `pop`, `print`.

3. **Binary Tree Implementation:**
   - Attributes: `size`, `root`.
   - Methods: `breadth_first_print`, `infix_print`.

4. **Binary Search Tree (BST) Implementation:**
   - Inherits from Binary Tree.
   - Additional methods: `insert`, `search`, `min`, `max`.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/BinaryTree-DataStructures.git
   ```
2. Install Python (if not already installed).
3. Run the Python scripts:
   ```bash
   python main.py
   ```

---

## Usage

1. Create and manipulate a Stack:
   ```python
   s = Stack()
   s.push(1)
   s.print()
   s.pop()
   s.print()
   ```

2. Create and manipulate a Queue:
   ```python
   q = Queue()
   q.push(1)
   q.push(2)
   q.print()
   q.pop()
   q.print()
   ```

3. Create and manipulate a Binary Search Tree:
   ```python
   t = BST()
   t.root = Node(4)
   t.insert(5)
   t.insert(3)
   t.infix_print()
   t.search(5)
   ```

---

## Results

- Implemented reusable and efficient data structures.
- Demonstrated core tree operations, including traversal and search.
- Showcased the use of object-oriented programming for modular design.

---

## Author

- **Name:** Olha Nemkovych
- **Group:** FI-94
