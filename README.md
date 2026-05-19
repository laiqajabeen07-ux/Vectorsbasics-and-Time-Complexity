# Vector Basics (C++ DSA Journey) 🚀

Welcome to my repository for tracking foundational Data Structures and Algorithms (DSA) concepts in C++. This repository focuses on mastering **C++ Vectors**, memory management, and analyzing **Time & Space Complexity (Big O Notation)**.

---

## 🛠️ Concepts & Problems Covered

Here is the breakdown of the standard problems I implemented from scratch to understand vector mechanics and optimize performance:

### 1. Vector Reverse (Two-Pointer Technique)
* **Logic:** Used a `left` and `right` index pointer to swap elements in-place without creating a new vector.
* **Time Complexity:** $O(n)$ 
* **Space Complexity:** $O(1)$ (Optimized, no extra memory used)

### 2. Find Maximum Element (State Tracking)
* **Logic:** Linear search traversal to find the largest value in an unsorted user-defined vector.
* **Time Complexity:** $O(n)$
* **Space Complexity:** $O(1)$

### 3. Target Frequency Counter
* **Logic:** Counting how many times a specific user-defined `key` appears in the vector using a single loop.
* **Time Complexity:** $O(n)$
* **Space Complexity:** $O(1)$

---

## 💡 Key Takeaways & Learnings

* **Big O Awareness:** Learned the difference between fast operations like direct index access `v[i]` and `push_back()` ($O(1)$ amortized) versus heavy operations like shifting elements using `v.insert()` ($O(n)$).
* **Safe Coding practices:** Mastered variable initialization (preventing garbage values) and properly defining function scopes/return types in C++.
* **User-Defined Inputs:** Handled dynamic user inputs using both `push_back()` sizing and direct array-like index population.

---

## 💻 Tech Stack Used
* **Language:** C++17 / C++20
* **IDE:** Visual Studio
* **Version Control:** Git & GitHub
