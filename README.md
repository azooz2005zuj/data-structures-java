# 🧩 Data Structures & Algorithms
**Java | NetBeans | University Project**

A collection of core data structures and sorting algorithms implemented from scratch in Java, each as a standalone interactive console application.

---

## 📦 Projects

### 1. 🔗 Linked List
Interactive singly linked list with a menu-driven interface.

**Operations:**
- Insert: First, Last, At Position
- Remove: First, Last, By Value
- Update, Search, Print

---

### 2. 📋 Queue
Circular array-based queue implementation.

**Operations:**
- Enqueue / Dequeue
- Search, Update, Display
- Overflow & underflow handling

---

### 3. 🌳 Binary Tree
Recursive binary tree with visual console printing.

**Operations:**
- Populate (interactive node-by-node build)
- Search, Update, Delete (with successor replacement)
- Visual tree print (rotated sideways in console)

---

### 4. 🔀 Merge Sort
Recursive divide-and-conquer sorting algorithm.

- Splits array into halves recursively
- Merges sorted halves back together
- Displays array before and after sorting

---

### 5. ⚡ Quick Sort
Recursive partition-based sorting algorithm.

- Last element as pivot
- In-place partitioning
- Displays array before and after sorting

---

## 📁 File Structure

```
data-structures-java/
├── LinkedList/
│   └── src/linkedlist/
│       ├── LinkedList.java   # Main + menu
│       └── Node.java         # Node class with all operations
├── QueueProject/
│   └── src/queueproject/
│       ├── QueueProject.java # Main + menu
│       └── Queue.java        # Circular array queue
├── tree/
│   └── src/tree/
│       ├── Tree.java         # Main + menu
│       └── BinaryTree.java   # Full binary tree implementation
├── Merge/
│   └── src/merge/
│       └── Merge.java        # Merge sort + main
└── Quick/
    └── src/quick/
        └── Quick.java        # Quick sort + main
```

---

## ▶️ How to Run

### NetBeans IDE
1. Open NetBeans
2. File → Open Project → select any subfolder
3. Press **F6** to run

### Command Line
```bash
# Example: Linked List
javac -d bin src/linkedlist/*.java
java -cp bin linkedlist.LinkedList
```

---

## 🛠️ Tech Stack
- Java (JDK 8+)
- NetBeans IDE
