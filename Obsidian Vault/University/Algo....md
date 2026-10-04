# C++ → Data Structures → Algorithms Roadmap

> **Goal:** Review C++ quickly, learn Data Structures and Algorithms in parallel, and maximize problem-solving practice for university.

## Core Strategy

Don't do this:

```text
Finish C++
    ↓
Finish Data Structures
    ↓
Finish Algorithms
    ↓
Start Problem Solving
```

Instead:

```text
C++ Review
    ↓
Data Structure
    ↓
Algorithm / Pattern
    ↓
Problems
    ↓
Find Weakness
    ↓
Review
    ↓
More Problems
```

The target is approximately:

```text
20% Learning
80% Problem Solving
```

---

# Phase 0 — C++ Diagnostic Review

**Duration: 3–5 days**

Don't spend weeks relearning C++. Review only what you need for DSA.

## C++ Basics

-  Variables
    
-  Data types
    
-  Operators
    
-  `if / else`
    
-  `switch`
    
-  `for`
    
-  `while`
    
-  Functions
    

## C++ Concepts Important for DSA

-  Arrays
    
-  Strings
    
-  References
    
-  Pointers
    
-  `struct`
    
-  Classes
    
-  Recursion
    
-  Pass by value vs. reference
    
-  `const`
    
-  Dynamic memory
    

## STL

Learn/review:

```cpp
vector
string
pair
array
stack
queue
deque
set
unordered_set
map
unordered_map
priority_queue
```

Important algorithms:

```cpp
sort()
reverse()
find()
binary_search()
min()
max()
swap()
```

Also understand:

-  Iterators
    
-  Range-based `for` loops
    
-  `.size()`
    
-  `.push_back()`
    
-  `.pop_back()`
    

---

# Phase 1 — Big-O + Problem Solving

**Duration: 2–3 days**

Before going deep into DSA, understand time and space complexity.

## Big-O

Learn:

```text
O(1)
O(log n)
O(n)
O(n log n)
O(n²)
O(2ⁿ)
O(n!)
```

Example:

```cpp
for (int i = 0; i < n; i++)
    cout << i;
```

Complexity:

```text
O(n)
```

Nested loop:

```cpp
for (int i = 0; i < n; i++)
    for (int j = 0; j < n; j++)
        cout << i << j;
```

Complexity:

```text
O(n²)
```

## Practice

Don't just study Big-O.

Immediately solve small problems and calculate the complexity of your solutions.

---

# Phase 2 — Arrays + Strings

**Duration: ~1 week**

## Learn

-  Arrays
    
-  `vector`
    
-  Strings
    
-  Traversal
    
-  Searching
    
-  Insertion/deletion
    
-  Frequency counting
    
-  Prefix sums
    

Then learn:

-  Two pointers
    
-  Sliding window
    

## Problem Practice

Start with:

```text
Easy
Easy
Easy
Medium
Easy
Medium
```

Focus on understanding the solution rather than completing a specific number of problems.

---

# Phase 3 — Linked Lists

**Duration: 3–4 days**

## Learn

-  Singly linked list
    
-  Doubly linked list
    
-  Insertion
    
-  Deletion
    
-  Search
    
-  Reverse
    
-  Fast/slow pointers
    

## Problems

-  Reverse Linked List
    
-  Find Middle of Linked List
    
-  Detect Cycle
    
-  Merge Two Sorted Lists
    
-  Remove Duplicates
    
-  Remove Nth Node
    

---

# Phase 4 — Stack + Queue

**Duration: 3–4 days**

## Stack

Understand:

```text
push
pop
top
```

## Queue

Understand:

```text
push
pop
front
```

Then learn:

-  Deque
    
-  Priority Queue
    
-  Monotonic Stack
    

## Problems

-  Valid Parentheses
    
-  Next Greater Element
    
-  Min Stack
    
-  Queue Using Stacks
    
-  Stack Using Queues
    
-  Sliding Window Maximum
    

---

# Phase 5 — Recursion

**Duration: 4–5 days**

Recursion is extremely important because it leads directly into several advanced topics.

## Learn

-  Base case
    
-  Recursive case
    
-  Call stack
    
-  Recursion tree
    

Then:

```text
Recursion
    ↓
Backtracking
    ↓
Trees
    ↓
DFS
    ↓
Dynamic Programming
```

## Problems

-  Factorial
    
-  Fibonacci
    
-  Sum of an array
    
-  Reverse a string
    
-  Generate subsets
    
-  Generate permutations
    

---

# Phase 6 — Searching + Sorting

**Duration: ~1 week**

## Searching

-  Linear Search
    
-  Binary Search
    

## Sorting

Understand:

-  Bubble Sort
    
-  Selection Sort
    
-  Insertion Sort
    
-  Merge Sort
    
-  Quick Sort
    

For every algorithm, understand:

1. How it works
    
2. Time complexity
    
3. Space complexity
    
4. When it is useful
    

Then use the STL when appropriate:

```cpp
sort(v.begin(), v.end());
```

---

# Phase 7 — Hashing

**Duration: 3–4 days**

Learn:

```cpp
unordered_map
unordered_set
map
set
```

Understand:

-  Hashing
    
-  Frequency counting
    
-  Fast lookup
    
-  Collision concept
    
-  Average complexity
    
-  Ordered vs. unordered containers
    

## Problems

-  Two Sum
    
-  Contains Duplicate
    
-  Frequency problems
    
-  Group Anagrams
    
-  Longest Consecutive Sequence
    

---

# Phase 8 — Trees

**Duration: 1–2 weeks**

## Learn

-  Binary Trees
    
-  Tree terminology
    
-  DFS
    
-  BFS
    
-  Preorder
    
-  Inorder
    
-  Postorder
    
-  Level-order traversal
    
-  Binary Search Trees
    

Then:

-  Tree height
    
-  Lowest Common Ancestor
    
-  Balanced trees — concepts
    
-  Heap
    
-  Priority Queue
    

## Problems

-  Maximum Depth
    
-  Same Tree
    
-  Invert Binary Tree
    
-  Level Order Traversal
    
-  Validate BST
    
-  Lowest Common Ancestor
    
-  Kth Smallest Element
    
-  Path Sum
    

---

# Phase 9 — Graphs

**Duration: 1–2 weeks**

## Representation

Learn:

```text
Adjacency Matrix
Adjacency List
```

## Traversal

Learn:

```text
BFS
DFS
```

Then:

-  Connected Components
    
-  Cycle Detection
    
-  Shortest Path
    
-  Topological Sort
    
-  Weighted Graphs
    

Later:

-  Dijkstra
    
-  Union-Find / DSU
    
-  Minimum Spanning Tree
    

---

# Phase 10 — Core Algorithms

Now you're moving deeper into algorithms.

## Greedy

-  Activity Selection
    
-  Interval Problems
    
-  Scheduling
    
-  Fractional Knapsack
    

## Divide and Conquer

-  Merge Sort
    
-  Quick Sort
    
-  Binary Search
    

## Backtracking

-  Subsets
    
-  Permutations
    
-  Combinations
    
-  N-Queens
    

## Dynamic Programming

Start slowly:

```text
1D DP
   ↓
2D DP
   ↓
Knapsack
   ↓
Subsequence Problems
   ↓
Grid DP
```

Don't start DP until you're comfortable with recursion.

---

# Problem-Solving Method

For every new problem, follow this process.

## 1. Understand the Problem

Ask:

> What exactly is the problem asking?

---

## 2. Work Through Examples

Take the sample input and solve it manually.

---

## 3. Find a Brute-Force Solution

Ask:

> What's the simplest solution I can think of?

Don't worry about optimization yet.

---

## 4. Calculate Complexity

Ask:

> Is my solution fast enough?

---

## 5. Look for a Pattern

Ask whether the problem could involve:

```text
Two Pointers
Sliding Window
Hash Map
Binary Search
Stack
Queue
Heap
DFS
BFS
Greedy
Backtracking
Dynamic Programming
```

---

## 6. Code

Only after understanding the approach.

---

## 7. Review

Ask yourself:

> Could I solve this problem again tomorrow without looking at the solution?

If not, review it.

---

# How Long Should You Spend on a Problem?

## Easy

```text
15–20 minutes
```

## Medium

```text
30–45 minutes
```

## Hard

```text
45–60+ minutes
```

If you're completely stuck:

1. Read the **idea/hint**
    
2. Close the solution
    
3. Implement it yourself
    
4. Understand why it works
    
5. Try the problem again later
    

Avoid copying solutions immediately.

---

# Problem Progression

Don't randomly solve hundreds of problems.

Use this pattern:

```text
Learn Concept
     ↓
5–10 Easy Problems
     ↓
5–10 Medium Problems
     ↓
Mixed Problems
```

For example:

```text
Arrays
  ↓
Easy × 5
  ↓
Medium × 5
  ↓
Mixed × 5

Hashing
  ↓
Easy × 5
  ↓
Medium × 5
  ↓
Mixed × 5
```

The exact number isn't important.

**Understanding the patterns is more important than the problem count.**

---

# Daily Schedule

If you have **2–3 hours per day**:

### 30–45 minutes

**Learn/review a concept**

Example:

```text
Binary Search
```

### 60–90 minutes

**Solve problems**

Try them yourself first.

### 15–30 minutes

**Review mistakes**

Write:

```text
Problem:
What I tried:
Why it failed:
Correct idea:
Important pattern:
Time complexity:
Space complexity:
```

---

# 20% Learning / 80% Problems

Your study time should eventually look like:

```text
┌─────────────────────────────────────┐
│                                     │
│       20% Learning / Review         │
│                                     │
├─────────────────────────────────────┤
│                                     │
│                                     │
│       80% Problem Solving           │
│                                     │
│                                     │
│                                     │
└─────────────────────────────────────┘
```

For a 3-hour session:

```text
45 min → Learn / Review
2 hours → Problems
15 min → Review mistakes
```

---

# 12-Week Intensive Plan

|Week|Main Focus|
|---|---|
|**1**|C++ Review + STL|
|**2**|Big-O + Arrays|
|**3**|Strings + Two Pointers + Sliding Window|
|**4**|Linked Lists|
|**5**|Stack + Queue + Hashing|
|**6**|Recursion + Binary Search|
|**7**|Sorting + Heap / Priority Queue|
|**8**|Binary Trees|
|**9**|BST + Tree Problems|
|**10**|Graphs + BFS / DFS|
|**11**|Greedy + Backtracking|
|**12**|Dynamic Programming + Mixed Problems|

Adjust this based on your university syllabus.

---

# Complete Learning Order

```text
1. C++ Review
       ↓
2. STL
       ↓
3. Big-O
       ↓
4. Arrays + Strings
       ↓
5. Two Pointers
       ↓
6. Sliding Window
       ↓
7. Linked Lists
       ↓
8. Stack + Queue
       ↓
9. Hashing
       ↓
10. Recursion
       ↓
11. Binary Search
       ↓
12. Sorting
       ↓
13. Trees
       ↓
14. Heap / Priority Queue
       ↓
15. Graphs
       ↓
16. Greedy
       ↓
17. Backtracking
       ↓
18. Dynamic Programming
       ↓
19. Mixed Problem Solving
```

---

# The Two Parallel Tracks

You are **not** doing C++ first and DSA afterward.

You're doing them together:

```text
                   C++ Review
                       │
                       ▼
                    C++ STL
                       │
                       ▼
                Data Structure
                       │
                       ▼
                 Algorithm
                       │
                       ▼
                Problem Solving
                       │
                ┌──────┴──────┐
                ▼             ▼
             Easy          Medium
                │             │
                └──────┬──────┘
                       ▼
                 Mixed Problems
                       │
                       ▼
                Review Mistakes
                       │
                       ▼
                Next Topic
```

## Golden Rule

> **Don't finish C++ before starting DSA.**

Review C++ **just enough to implement the DSA you're currently studying**.

Your objective isn't to become an expert at C++ first.

Your objective is:

```text
C++ → DSA → Algorithms → Problems → Patterns → Better Problem Solving
```

**Problem solving is the main skill.**