# 30-Day PHP Data Structures & Algorithms (DSA) Learning Plan

**Duration:** 30 days\
**Daily commitment:** 30 minutes\
**Total study time:** 15 hours\
**Language:** PHP

## Learning goal

Build a practical foundation in Data Structures and Algorithms using
PHP. By the end of the plan, you should be able to implement common data
structures, explain their operations and time complexity, and apply them
to small programming problems.

## Daily study routine

Use this structure every day:

  Activity                                              Time
  ----------------------------------------- ----------------
  Learn the concept                               10 minutes
  Implement it in PHP                             15 minutes
  Test, review, and note what you learned          5 minutes
  **Total**                                   **30 minutes**

Try to write the implementation yourself before looking at a reference
solution.

------------------------------------------------------------------------

## Week 1 --- PHP fundamentals and linear structures

**Goal:** Become comfortable with arrays, complexity, and the basic
linear data structures.

  ------------------------------------------------------------------------
                           Day Topic                 Practical exercise
  ---------------------------- --------------------- ---------------------
                             1 PHP arrays: indexed   Create arrays, read
                               and associative       values, add items,
                                                     remove items, and
                                                     iterate

                             2 Multidimensional      Build and query a
                               arrays                student-records array

                             3 Array operations      Practice
                                                     `array_map()`,
                                                     `array_filter()`, and
                                                     `array_reduce()`

                             4 Time and space        Understand Big O:
                               complexity            O(1), O(n), O(n²),
                                                     and O(log n)

                             5 Stack (LIFO)          Implement a Stack
                                                     class with `push()`,
                                                     `pop()`, and `peek()`

                             6 Queue (FIFO)          Implement a Queue
                                                     class with
                                                     `enqueue()` and
                                                     `dequeue()`

                             7 Singly linked list    Implement nodes,
                                                     insertion, deletion,
                                                     search, and traversal
  ------------------------------------------------------------------------

**Week 1 deliverable:** Your own Stack, Queue, and Singly Linked List
implementations.

## Week 2 --- Linear structures and core algorithms

**Goal:** Extend your understanding of linked lists, searching, sorting,
recursion, and hashing.

  ------------------------------------------------------------------------
                           Day Topic                 Practical exercise
  ---------------------------- --------------------- ---------------------
                             8 Doubly linked list    Implement insertion,
                                                     deletion, and
                                                     forward/backward
                                                     traversal

                             9 Circular linked list  Build a circular
                                                     linked list and
                                                     traverse it safely

                            10 Searching algorithms  Implement Linear
                                                     Search and Binary
                                                     Search

                            11 Bubble Sort and       Sort an array
                               Selection Sort        manually and compare
                                                     the approaches

                            12 Insertion Sort and    Implement both
                               Merge Sort            algorithms and
                                                     compare their
                                                     complexity

                            13 Recursion             Solve factorial,
                                                     Fibonacci, and
                                                     recursive array
                                                     traversal

                            14 Hash tables / maps    Explore PHP
                                                     associative arrays
                                                     and implement a basic
                                                     hash-map concept
  ------------------------------------------------------------------------

**Week 2 deliverable:** A small PHP collection of linked-list,
searching, and sorting implementations.

## Week 3 --- Non-linear data structures

**Goal:** Understand trees, heaps, priority queues, and graphs.

  ------------------------------------------------------------------------
                           Day Topic                 Practical exercise
  ---------------------------- --------------------- ---------------------
                            15 Binary trees          Create a Binary Tree
                                                     using PHP classes

                            16 Binary Search Trees   Implement insertion
                               (BST)                 and search

                            17 Tree traversal        Implement Inorder,
                                                     Preorder, and
                                                     Postorder traversal

                            18 Heaps                 Implement Min Heap
                                                     and Max Heap

                            19 Priority queues       Build a task-priority
                                                     manager using
                                                     `SplPriorityQueue` or
                                                     your own
                                                     implementation

                            20 Graphs                Represent a graph
                                                     using an adjacency
                                                     list

                            21 Graph traversal       Implement
                                                     Breadth-First Search
                                                     (BFS) and Depth-First
                                                     Search (DFS)
  ------------------------------------------------------------------------

**Week 3 deliverable:** A small task-priority manager and working graph
traversal implementations.

## Week 4 --- Practical techniques and problem solving

**Goal:** Apply DSA concepts to common programming challenges and
consolidate your learning.

  ------------------------------------------------------------------------
                           Day Topic                 Practical exercise
  ---------------------------- --------------------- ---------------------
                            22 Trie                  Build a simple
                                                     autocomplete or
                                                     prefix-search system

                            23 Set data structure    Implement
                                                     unique-value
                                                     management and set
                                                     operations

                            24 Two-pointer technique Solve pair-sum and
                                                     duplicate-removal
                                                     problems

                            25 Sliding-window        Find the maximum sum
                               technique             of a fixed-size
                                                     subarray

                            26 Dynamic programming   Solve Fibonacci using
                                                     memoization and
                                                     tabulation

                            27 Greedy algorithms     Implement a greedy
                                                     coin-change example
                                                     and understand when
                                                     it may not be optimal

                            28 Problem-solving       Solve three array or
                               practice              string problems and
                                                     explain your approach

                            29 Practical project     Build an in-memory
                                                     task manager using
                                                     suitable data
                                                     structures

                            30 Final review          Revisit Big O, test
                                                     implementations, and
                                                     document what you
                                                     learned
  ------------------------------------------------------------------------

**Week 4 deliverable:** A mini PHP DSA library and a working in-memory
task manager.

------------------------------------------------------------------------

## Suggested project structure

Organize your practice code so each topic is easy to find and test.

``` text
php-dsa/
├── src/
│   ├── Arrays/
│   ├── Stack/
│   ├── Queue/
│   ├── LinkedList/
│   ├── Searching/
│   ├── Sorting/
│   ├── Trees/
│   ├── Heaps/
│   ├── Graphs/
│   └── Algorithms/
├── tests/
├── composer.json
└── README.md
```

Use PHP classes, namespaces, type declarations, and PHPUnit tests as you
become comfortable. You do not need to introduce all of these tools on
Day 1.

## Operations to practise

For each data structure, identify which operations make sense and
implement them where applicable:

1.  Insert
2.  Delete
3.  Search
4.  Update
5.  Traverse

Record the time complexity of each operation. Not every structure
supports every operation in the same way.

## Progress checklist

-   [ ] Complete the 30 daily study sessions.
-   [ ] Implement at least 10 data structures or core techniques
    yourself.
-   [ ] Explain common Big O time and space complexities.
-   [ ] Solve at least 15 programming problems.
-   [ ] Write reusable PHP classes and test them.
-   [ ] Explain when and why you would choose each data structure.
-   [ ] Complete the final practical project.

## Recommended learning resources

-   [PHP Manual](https://www.php.net/manual/en/)
-   [PHP SPL documentation](https://www.php.net/manual/en/book.spl.php)
-   [VisuAlgo --- algorithm visualizations](https://visualgo.net/en)
-   [LeetCode --- coding practice](https://leetcode.com/)

## Important learning advice

-   Prefer understanding and implementing a structure yourself over
    memorizing code.
-   Test normal cases, empty structures, duplicate values, and boundary
    cases.
-   Keep a short note each day: what the structure does, when it is
    useful, and its operation complexities.
-   PHP's SPL provides useful built-in structures, but implement core
    structures manually during this plan to understand how they work.
-   If a topic takes longer than 30 minutes, continue it in the next
    session rather than rushing through it.

**Success target:** By the end of Day 30, you should have a tested
collection of PHP DSA exercises, a clearer understanding of complexity,
and the confidence to choose suitable data structures for practical
problems.
