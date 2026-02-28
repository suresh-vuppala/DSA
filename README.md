# DSA

---

## 📚 Table of Contents

1. [📝 Programming Essentials & Arrays](#-programming-essentials--arrays)
2. [🔀 Subarrays · Subsets · Subsequences · Bit Manipulation · Recursion · Backtracking](#-subarrays--subsets--subsequences--bit-manipulation--recursion--backtracking)
3. [🔃 Sorting Algorithms & Two Pointers](#-sorting-algorithms--two-pointers)
4. [🔍 Searching Algorithms & Binary Search](#-searching-algorithms--binary-search)
5. [📐 Essential Math, Game Theory & Hashing](#-essential-math-game-theory--hashing)
6. [🖼️ Sliding Window, Strings & Rolling Hash](#️-sliding-window-strings--rolling-hash)
7. [📊 Prefix Sum](#-prefix-sum)
8. [🥞 Stack, Queue & Deque](#-stack-queue--deque)
9. [⛓️ Linked Lists](#️-linked-lists)
10. [🌳 Trees & Binary Search Trees](#-trees--binary-search-trees)
11. [🌲 Advanced Tree Problems](#-advanced-tree-problems)
12. [🔺 Heaps & Priority Queue](#-heaps--priority-queue)
13. [💻 Dynamic Programming](#-dynamic-programming)
14. [🧱 Advanced DP & Graph Introduction](#-advanced-dp--graph-introduction)
15. [🌐 Graph Algorithms](#-graph-algorithms)

---

*   **Legend:**
    *   ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square)
    *   ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square)
    *   ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square)
    *   ⭐ = Especially High Frequency / Foundational

---

## 📝 Programming Essentials & Arrays

> **Focus:** Getting started with easy problems · Anatomy of a problem statement · Input/Output · Arrays · Time & Space Complexity (Iterative & Recursive) · Common Complexities and Constraints

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 1   | ⭐ **[Two Sum](https://leetcode.com/problems/two-sum/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing | The quintessential hash map problem. Checks basic data structure usage. | LC Top, Blind 75 |
| 2   | **[Contains Duplicate](https://leetcode.com/problems/contains-duplicate/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing, Set | Basic set usage for uniqueness checks. | LC Top |
| 3   | ⭐ **[Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Greedy, One Pass | Simple optimization — finding min/max efficiently in one pass. | LC Top, Blind 75 |
| 4   | ⭐ **[Maximum Subarray](https://leetcode.com/problems/maximum-subarray/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Kadane's Algo, DP | The most famous DP intro problem (can be solved greedily). Fundamental pattern. | LC Top, Blind 75 |
| 5   | ⭐ **[Product of Array Except Self](https://leetcode.com/problems/product-of-array-except-self/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix/Suffix Products | Clever array manipulation without division. Tests thinking outside the box. | LC Top, Blind 75 |
| 6   | **[Maximum Product Subarray](https://leetcode.com/problems/maximum-product-subarray/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, Array Traversal | Variation of Max Subarray — handles negatives. Tests edge cases. | LC Top, Blind 75 |
| 7   | **[Next Permutation](https://leetcode.com/problems/next-permutation/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Array Manipulation | Understanding lexicographical order and in-place swaps. | LC Top |
| 8   | **[Find the Duplicate Number](https://leetcode.com/problems/find-the-duplicate-number/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Cycle Detection (Floyd's) | Maps array problem to linked list cycle detection. Clever and efficient. | LC Top |

---

## 🔀 Subarrays · Subsets · Subsequences · Bit Manipulation · Recursion · Backtracking

> **Focus:** Understanding Subarrays vs Subsets vs Subsequences · Bit tricks · Recursive thinking · Backtracking template

### 📐 Math & Bit Manipulation

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 9   | **[Number of 1 Bits](https://leetcode.com/problems/number-of-1-bits/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation | Basic bit counting (Hamming weight). | LC Top, Blind 75 |
| 10  | **[Counting Bits](https://leetcode.com/problems/counting-bits/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation, DP | Calculating bits for 0 to n efficiently using DP relation. | LC Top, Blind 75 |
| 11  | **[Reverse Bits](https://leetcode.com/problems/reverse-bits/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation | Reversing bits of an integer. Tests careful bit shifting and masking. | LC Top, Blind 75 |
| 12  | **[Missing Number](https://leetcode.com/problems/missing-number/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation (XOR), Math | Finding the missing number using XOR properties or sum formula. | LC Top, Blind 75 |
| 13  | ⭐ **[Sum of Two Integers](https://leetcode.com/problems/sum-of-two-integers/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Bit Manipulation | Adding numbers without `+` or `-`. Tests understanding of bitwise addition. | LC Top, Blind 75 |

### 🔙 Backtracking

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 14  | ⭐ **[Subsets](https://leetcode.com/problems/subsets/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Generating all possible combinations (powerset). Foundational backtracking. | LC Top, Blind 75 |
| 15  | **[Subsets II](https://leetcode.com/problems/subsets-ii/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Sorting | Subsets with duplicate elements. Requires careful duplicate handling. | LC Top, NeetCode |
| 16  | **[Combination Sum](https://leetcode.com/problems/combination-sum/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Finding combinations that sum to a target (with repetition allowed). | LC Top, Blind 75 |
| 17  | **[Combination Sum II](https://leetcode.com/problems/combination-sum-ii/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Sorting | Combination sum with duplicates — ensures unique combinations. | LC Top, NeetCode |
| 18  | **[Permutations](https://leetcode.com/problems/permutations/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Generating all orderings of elements. | LC Top, Blind 75 |
| 19  | ⭐ **[Word Search](https://leetcode.com/problems/word-search/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, DFS | Classic grid backtracking — searching for a word in a 2D board. | LC Top, Blind 75 |
| 20  | **[Letter Combinations of a Phone Number](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Mapping digits to letters and generating combinations. | LC Top, NeetCode |
| 21  | **[Palindrome Partitioning](https://leetcode.com/problems/palindrome-partitioning/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, DP | Partitioning a string into palindromic substrings. | LC Top, NeetCode |
| 22  | **[N-Queens](https://leetcode.com/problems/n-queens/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Backtracking | Quintessential constraint satisfaction backtracking problem. | LC Top |

---

## 🔃 Sorting Algorithms & Two Pointers

> **Focus:** Bubble Sort · Insertion Sort · Selection Sort · Merge Sort & Applications · Introduction to Two Pointer Technique · Comparisons & Classifications

### ⚖️ Two Pointers

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 23  | ⭐ **[3Sum](https://leetcode.com/problems/3sum/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sorting, Two Pointers | Foundational k-sum problem. Tests handling duplicates and two-pointer technique. | LC Top, Blind 75 |
| 24  | **[Container With Most Water](https://leetcode.com/problems/container-with-most-water/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers | Classic two-pointer optimization problem. | LC Top, Blind 75 |
| 25  | ⭐ **[Valid Palindrome](https://leetcode.com/problems/valid-palindrome/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Two Pointers, String | Basic two-pointer technique for symmetry checks, ignoring non-alphanumerics. | LC Top, Blind 75 |
| 26  | **[Sort Colors](https://leetcode.com/problems/sort-colors/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers | Dutch National Flag problem. Efficient in-place partitioning. | LC Top |
| 27  | **[Trapping Rain Water](https://leetcode.com/problems/trapping-rain-water/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Two Pointers, DP, Stack | Multiple solutions exist. Tests optimization and insights. | LC Top, NeetCode |

---

## 🔍 Searching Algorithms & Binary Search

> **Focus:** Linear Search · Binary Search · Applications of Binary Search · Binary Search the Answer

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 28  | ⭐ **[Binary Search](https://leetcode.com/problems/binary-search/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Binary Search | The core algorithm itself. Essential foundation. | LC Top |
| 29  | **[Search a 2D Matrix](https://leetcode.com/problems/search-a-2d-matrix/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Applying binary search on a conceptually flattened sorted 2D matrix. | LC Top, Blind 75 |
| 30  | **[Find Minimum in Rotated Sorted Array](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Classic modified binary search on rotated arrays. | LC Top, Blind 75 |
| 31  | ⭐ **[Search in Rotated Sorted Array](https://leetcode.com/problems/search-in-rotated-sorted-array/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Extends the above — requires careful boundary condition handling. | LC Top, Blind 75 |
| 32  | **[Koko Eating Bananas](https://leetcode.com/problems/koko-eating-bananas/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search on Answer | Searching for the minimum speed (the answer) within a possible range. | NeetCode |
| 33  | **[Time Based Key-Value Store](https://leetcode.com/problems/time-based-key-value-store/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Binary Search | Searching for a value based on timestamp. Requires binary search on timestamps. | LC Top, Blind 75 |
| 34  | ⭐ **[Median of Two Sorted Arrays](https://leetcode.com/problems/median-of-two-sorted-arrays/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Binary Search | Advanced binary search on partitions to find the median efficiently. | LC Top, Blind 75 |

---

## 📐 Essential Math, Game Theory & Hashing

> **Focus:** Prime Numbers · Sieve of Eratosthenes · Segmented Sieve · Modular Arithmetic · Game Theory · Introduction to Hashing

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 35  | **[Reverse Integer](https://leetcode.com/problems/reverse-integer/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Math, Overflow Check | Reversing digits of an integer while handling potential overflow. | LC Top |
| 36  | **[Pow(x, n)](https://leetcode.com/problems/powx-n/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Recursion, Math | Efficient exponentiation using recursion (exponentiation by squaring). | LC Top |
| 37  | **[Rotate Image](https://leetcode.com/problems/rotate-image/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Math, Matrix | Rotating a matrix in-place. Tests index manipulation. | LC Top, NeetCode |
| 38  | **[Spiral Matrix](https://leetcode.com/problems/spiral-matrix/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Matrix Traversal | Traversing a matrix in a spiral pattern. Tests boundary and direction handling. | LC Top, NeetCode |
| 39  | **[Set Matrix Zeroes](https://leetcode.com/problems/set-matrix-zeroes/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Matrix, Space Optimization | Setting rows/columns to zero efficiently, often using O(1) extra space. | LC Top, NeetCode |
| 40  | ⭐ **[Group Anagrams](https://leetcode.com/problems/group-anagrams/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Sorting | Grouping items based on a derived key (sorted string or char count). | LC Top, Blind 75 |
| 41  | ⭐ **[Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Heap, QuickSelect | Finding most frequent items efficiently. Tests Heap or QuickSelect usage. | LC Top, Blind 75 |

---

## 🖼️ Sliding Window, Strings & Rolling Hash

> **Focus:** Sliding Window Technique · Maximum Sum of K Consecutive Elements · String Problems · Rolling Hash · Substring Matching · Rabin-Karp · Longest Common Substring

### 🖼️ Sliding Window

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 42  | ⭐ **[Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | The canonical sliding window problem. Tests efficient substring analysis. | LC Top, Blind 75 |
| 43  | ⭐ **[Longest Repeating Character Replacement](https://leetcode.com/problems/longest-repeating-character-replacement/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | Advanced sliding window requiring careful window condition management. | LC Top, Blind 75 |
| 44  | **[Permutation in String](https://leetcode.com/problems/permutation-in-string/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | Fixed-size window check using frequency maps. | LC Top, Blind 75 |
| 45  | ⭐ **[Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Sliding Window, Hashing | The definitive challenging sliding window problem. Tests complex state tracking. | LC Top, Blind 75 |

### ✍️ Strings

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 46  | ⭐ **[Valid Anagram](https://leetcode.com/problems/valid-anagram/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing, Sorting | Fundamental check for character counts. Basic but essential. | LC Top, Blind 75 |
| 47  | ⭐ **[Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Stack | Classic stack application for matching pairs. | LC Top, Blind 75 |
| 48  | ⭐ **[Longest Palindromic Substring](https://leetcode.com/problems/longest-palindromic-substring/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Expand Around Center, DP | Finding optimal substructures. Expand-around-center is often preferred. | LC Top, Blind 75 |
| 49  | **[Palindromic Substrings](https://leetcode.com/problems/palindromic-substrings/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Expand Around Center, DP | Counting all palindromic substrings. Similar logic to above but counting. | LC Top, Blind 75 |
| 50  | **[Encode and Decode Strings](https://leetcode.com/problems/encode-and-decode-strings/)** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | String Design, Delimiter | Practical problem often asked in system design contexts. Tests edge cases. | Blind 75, NeetCode |

---

## 📊 Prefix Sum

> **Focus:** Prefix Sum / Cumulative Sum · Range Sum Queries · Subarray Sum Problems · 2D Prefix Sum

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 51  | ⭐ **[Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-immutable/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Prefix Sum | The canonical prefix sum problem. Foundation for range queries. | LC Top |
| 52  | **[Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Hashing | Finding subarrays with target sum efficiently using prefix sums. | LC Top, NeetCode |
| 53  | **[Continuous Subarray Sum](https://leetcode.com/problems/continuous-subarray-sum/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Modulo | Range sum with modular arithmetic constraint. Tests prefix sum insights. | LC Top, NeetCode |
| 54  | **[2D Range Sum Query - Immutable](https://leetcode.com/problems/range-sum-query-2d-immutable/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | 2D Prefix Sum | Extending prefix sum to 2D grids for efficient area queries. | LC Top |
| 55  | **[Longest Well-Performing Interval](https://leetcode.com/problems/longest-well-performing-interval/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Hashing | Converting problem to finding longest subarray with sum > 0. | LC Top, NeetCode |
| 56  | ⭐ **[Longest Balanced Substring II](https://leetcode.com/problems/longest-balanced-substring-ii/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Prefix Sum, String | Advanced string balancing problem solved efficiently using prefix sum patterns. | LC Top |

---

## 🥞 Stack, Queue & Deque

> **Focus:** Stack · Queue · Deque · Circular Queue · Monotonic Stack patterns

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 57  | **[Min Stack](https://leetcode.com/problems/min-stack/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Stack Design | Designing a stack with O(1) min retrieval. Tests data structure design. | LC Top, NeetCode |
| 58  | **[Evaluate Reverse Polish Notation](https://leetcode.com/problems/evaluate-reverse-polish-notation/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Stack | Direct stack application for expression evaluation. | LC Top |
| 59  | **[Daily Temperatures](https://leetcode.com/problems/daily-temperatures/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Monotonic Stack | Classic "next greater element" pattern using a monotonic stack. | LC Top, NeetCode |
| 60  | **[Largest Rectangle in Histogram](https://leetcode.com/problems/largest-rectangle-in-histogram/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Monotonic Stack | Challenging application of monotonic stack for area calculation. | LC Top, NeetCode |

---

## ⛓️ Linked Lists

> **Focus:** Linked List operations · Classic Linked List Problems

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 61  | ⭐ **[Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Iteration, Recursion | The absolute fundamental linked list manipulation. | LC Top, Blind 75 |
| 62  | ⭐ **[Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Floyd's Cycle Detection | Classic application of the Tortoise and Hare algorithm. | LC Top, Blind 75 |
| 63  | ⭐ **[Merge Two Sorted Lists](https://leetcode.com/problems/merge-two-sorted-lists/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Pointers, Iteration | Foundational merging logic, basis for Merge Sort. | LC Top, Blind 75 |
| 64  | **[Remove Nth Node From End of List](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers (Fast/Slow) | Common two-pointer pattern for finding elements relative to the end. | LC Top, Blind 75 |
| 65  | **[Reorder List](https://leetcode.com/problems/reorder-list/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Find Middle, Reverse, Merge | Combines multiple core list operations. Good test of modular thinking. | LC Top, Blind 75 |
| 66  | ⭐ **[Merge k Sorted Lists](https://leetcode.com/problems/merge-k-sorted-lists/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Heap (Priority Queue), D&C | Scalable merging. Tests heap usage or divide-and-conquer approach. | LC Top, Blind 75 |

---

## 🌳 Trees & Binary Search Trees

> **Focus:** Tree Traversals (Inorder, Preorder, Postorder) · BFS / DFS · Standard Tree Problems · BST Insert / Search / Delete · Recursive & Iterative Traversals

### 🌳 Tree Traversal & BFS/DFS

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 67  | ⭐ **[Maximum Depth of Binary Tree](https://leetcode.com/problems/maximum-depth-of-binary-tree/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Basic recursive tree traversal. | LC Top, Blind 75 |
| 68  | ⭐ **[Same Tree](https://leetcode.com/problems/same-tree/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Basic structural comparison using recursion. | LC Top, Blind 75 |
| 69  | ⭐ **[Invert Binary Tree](https://leetcode.com/problems/invert-binary-tree/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS/BFS, Recursion | Famous, simple tree manipulation via recursion or iteration. | LC Top, Blind 75 |
| 70  | **[Subtree of Another Tree](https://leetcode.com/problems/subtree-of-another-tree/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Recursive check involving a helper for subtree matching. | LC Top, Blind 75 |
| 71  | **[Diameter of Binary Tree](https://leetcode.com/problems/diameter-of-binary-tree/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Calculating longest path via recursive depth calculation. | LC Top, NeetCode |
| 72  | ⭐ **[Binary Tree Level Order Traversal](https://leetcode.com/problems/binary-tree-level-order-traversal/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS, Queue | The canonical BFS application on trees. | LC Top, Blind 75 |
| 73  | **[Binary Tree Right Side View](https://leetcode.com/problems/binary-tree-right-side-view/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS, DFS | Variation of level order traversal (finding the last node at each level). | LC Top, NeetCode |

### 🌲 Binary Search Trees

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 74  | ⭐ **[Validate Binary Search Tree](https://leetcode.com/problems/validate-binary-search-tree/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DFS, Recursion, Range | Checking BST validity requires passing down min/max constraints. | LC Top, Blind 75 |
| 75  | ⭐ **[Kth Smallest Element in a BST](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Inorder Traversal, DFS | Leverages the inorder traversal property of BSTs. | LC Top, Blind 75 |
| 76  | ⭐ **[Lowest Common Ancestor of a BST](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-search-tree/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BST Properties, DFS | Utilizes BST properties for efficient LCA finding. | LC Top, Blind 75 |

---

## 🌲 Advanced Tree Problems

> **Focus:** Advanced Trees · Trie · Complex recursive patterns

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 77  | **[Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Recursion, Hashing | Classic tree construction problem using traversal properties. | LC Top, Blind 75 |
| 78  | **[Implement Trie (Prefix Tree)](https://leetcode.com/problems/implement-trie-prefix-tree/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, Design | Foundational for many string/dictionary problems. | LC Top, Blind 75 |
| 79  | **[Design Add and Search Words Data Structure](https://leetcode.com/problems/design-add-and-search-words-data-structure/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, DFS, Backtracking | Extends Trie with wildcard search. Tests recursive search logic. | LC Top, Blind 75 |
| 80  | ⭐ **[Binary Tree Maximum Path Sum](https://leetcode.com/problems/binary-tree-maximum-path-sum/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DFS, Recursion | Tricky recursion where path can start/end anywhere. Requires careful state return. | LC Top, Blind 75 |
| 81  | **[Serialize and Deserialize Binary Tree](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DFS/BFS, String | Design problem involving tree representation as a string. | LC Top, Blind 75 |
| 82  | **[Word Search II](https://leetcode.com/problems/word-search-ii/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Trie, Backtracking, DFS | Combines Trie efficiency with grid backtracking. Highly practical. | LC Top, Blind 75 |

---

## 🔺 Heaps & Priority Queue

> **Focus:** Min/Max Heap · Heap Sort · Classic Heap Problems

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 83  | **[Kth Largest Element in an Array](https://leetcode.com/problems/kth-largest-element-in-an-array/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Heap, QuickSelect | Finding the specific Kth element efficiently. | LC Top, NeetCode |
| 84  | **[Task Scheduler](https://leetcode.com/problems/task-scheduler/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Heap, Hashing | Scheduling tasks with cooldowns — solved greedily or with a max-heap. | LC Top, NeetCode |
| 85  | **[Find Median from Data Stream](https://leetcode.com/problems/find-median-from-data-stream/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Two Heaps (Max/Min) | Classic design problem using two heaps to maintain median in streaming fashion. | LC Top, Blind 75 |

---

## 💻 Dynamic Programming

> **Focus:** Nth Fibonacci Number · Memoization · Tabulation · Classic DP Problems

### 💻 1D Dynamic Programming

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 86  | ⭐ **[Climbing Stairs](https://leetcode.com/problems/climbing-stairs/)** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DP (Fibonacci) | The introductory DP problem, equivalent to Fibonacci sequence. | LC Top, Blind 75 |
| 87  | ⭐ **[Coin Change](https://leetcode.com/problems/coin-change/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Unbounded Knapsack) | Classic DP for minimum coins. Tests state definition and transitions. | LC Top, Blind 75 |
| 88  | ⭐ **[Longest Increasing Subsequence](https://leetcode.com/problems/longest-increasing-subsequence/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, Binary Search | Fundamental subsequence problem. Can be optimized with Binary Search. | LC Top, Blind 75 |
| 89  | ⭐ **[Word Break](https://leetcode.com/problems/word-break/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, String | Checking if a string can be segmented using a dictionary. Common string DP. | LC Top, Blind 75 |
| 90  | ⭐ **[House Robber](https://leetcode.com/problems/house-robber/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP | Simple 1D DP with non-adjacent constraint. | LC Top, Blind 75 |
| 91  | **[House Robber II](https://leetcode.com/problems/house-robber-ii/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP | Circular variation of House Robber. Tests reducing to subproblems. | LC Top, Blind 75 |
| 92  | **[Decode Ways](https://leetcode.com/problems/decode-ways/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, String | Counting ways to decode a numeric string. Tests handling DP states carefully. | LC Top, Blind 75 |
| 93  | **[Partition Equal Subset Sum](https://leetcode.com/problems/partition-equal-subset-sum/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (0/1 Knapsack) | Subset sum variation. Tests boolean DP state. | LC Top, NeetCode |

### 🧱 2D & Advanced Dynamic Programming

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 94  | **[Unique Paths](https://leetcode.com/problems/unique-paths/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Grid) | Basic 2D DP on a grid. Calculating paths from top-left to bottom-right. | LC Top, Blind 75 |
| 95  | **[Longest Common Subsequence](https://leetcode.com/problems/longest-common-subsequence/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (2D String) | Fundamental DP for comparing two sequences. | LC Top, Blind 75 |
| 96  | **[Edit Distance](https://leetcode.com/problems/edit-distance/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (2D String) | Classic DP for string transformation distance (Levenshtein). | LC Top, NeetCode |
| 97  | **[Maximal Square](https://leetcode.com/problems/maximal-square/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Grid) | Finding the largest square of 1s in a binary matrix. | LC Top |
| 98  | **[Best Time to Buy and Sell Stock with Cooldown](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (State Machine) | Stock problem requiring state machine DP (buy, sell, cooldown). | LC Top, NeetCode |
| 99  | **[Burst Balloons](https://leetcode.com/problems/burst-balloons/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DP (Interval) | Challenging interval DP. Requires thinking about the last operation. | LC Top, NeetCode |
| 100 | **[Regular Expression Matching](https://leetcode.com/problems/regular-expression-matching/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DP, Recursion | Complex DP with `'.'` and `'*'`. Tests careful state transitions. | LC Top |

---

## 🧱 Advanced DP & Graph Introduction

> **Focus:** Advanced DP Problems · Introduction to Graphs

### 🧩 Intervals (Advanced DP adjacent)

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 101 | ⭐ **[Insert Interval](https://leetcode.com/problems/insert-interval/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Interval Merging | Inserting a new interval into sorted, non-overlapping intervals and merging. | LC Top, Blind 75 |
| 102 | ⭐ **[Merge Intervals](https://leetcode.com/problems/merge-intervals/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sorting, Intervals | The canonical interval merging problem after sorting by start time. | LC Top, Blind 75 |
| 103 | ⭐ **[Non-overlapping Intervals](https://leetcode.com/problems/non-overlapping-intervals/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Sorting | Finding minimum removals to make intervals non-overlapping. | LC Top, Blind 75 |
| 104 | **[Meeting Rooms](https://leetcode.com/problems/meeting-rooms/)** *(Premium)* | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Sorting, Intervals | Checking if a person can attend all meetings (no overlaps). | Blind 75, NeetCode |
| 105 | ⭐ **[Meeting Rooms II](https://leetcode.com/problems/meeting-rooms-ii/)** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Heap, Sorting | Finding the minimum number of rooms required. | Blind 75, NeetCode |
| 106 | **[Minimum Interval to Include Each Query](https://leetcode.com/problems/minimum-interval-to-include-each-query/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Heap, Sorting, Sweep Line | Advanced interval querying using heaps and sorting. | NeetCode |

---

## 🌐 Graph Algorithms

> **Focus:** Graph Traversals (BFS & DFS) · Dijkstra's Algorithm · Topological Sorting · Bipartite Graphs · Kruskal's Algorithm · Union-Find

### Graph BFS / DFS

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 107 | ⭐ **[Number of Islands](https://leetcode.com/problems/number-of-islands/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Grid | The fundamental graph traversal problem on a grid. Counts connected components. | LC Top, Blind 75 |
| 108 | ⭐ **[Clone Graph](https://leetcode.com/problems/clone-graph/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Hashing | Deep copying graph structure. Tests handling visited nodes. | LC Top, Blind 75 |
| 109 | **[Pacific Atlantic Water Flow](https://leetcode.com/problems/pacific-atlantic-water-flow/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Grid | Multi-source traversal from oceans inward. Tests simultaneous graph traversals. | LC Top, Blind 75 |

### Dijkstra's Algorithm (Shortest Path)

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 110 | **[Network Delay Time](https://leetcode.com/problems/network-delay-time/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Dijkstra's/Bellman-Ford | Shortest path from a source in a weighted directed graph. | LC Top, NeetCode |
| 111 | **[Cheapest Flights Within K Stops](https://leetcode.com/problems/cheapest-flights-within-k-stops/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Bellman-Ford / Modified Dijkstra | Shortest path with constraint on number of edges. | NeetCode |
| 112 | ⭐ **[Word Ladder](https://leetcode.com/problems/word-ladder/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | BFS, Implicit Graph | Shortest path on an implicit graph where edges are word transformations. | LC Top, Blind 75 |

### Topological Sorting & Bipartite Graphs

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 113 | ⭐ **[Course Schedule](https://leetcode.com/problems/course-schedule/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Topological Sort (DFS/BFS) | Detecting cycles in a directed graph (prerequisite check). Essential pattern. | LC Top, Blind 75 |
| 114 | **[Course Schedule II](https://leetcode.com/problems/course-schedule-ii/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Topological Sort | Finding a valid course order. Extends Course Schedule I. | LC Top, NeetCode |
| 115 | **[Alien Dictionary](https://leetcode.com/problems/alien-dictionary/)** *(Premium)* | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Topological Sort, Graph Building | Deriving character order from a sorted word list. Complex graph construction. | Blind 75, NeetCode |

### Union-Find (Kruskal's / Connectivity)

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 116 | **[Redundant Connection](https://leetcode.com/problems/redundant-connection/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find | Finding the edge that creates a cycle. Classic Union-Find application. | NeetCode |
| 117 | **[Number of Connected Components](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/)** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find, BFS/DFS | Basic connectivity check using Union-Find. | Blind 75, NeetCode |
| 118 | **[Graph Valid Tree](https://leetcode.com/problems/graph-valid-tree/)** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find, BFS/DFS | Checking if a graph is a tree (connected and acyclic). | Blind 75, NeetCode |
| 119 | **[Critical Connections in a Network](https://leetcode.com/problems/critical-connections-in-a-network/)** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Tarjan's Algorithm (Bridges) | Finding bridges in a graph. Tests understanding of advanced graph algorithms. | NeetCode |

---

## 💡 Greedy

> Greedy problems are woven throughout the curriculum but highlighted here for reference

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 120 | **[Jump Game](https://leetcode.com/problems/jump-game/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy | Checking reachability by tracking the maximum reachable index greedily. | LC Top, Blind 75 |
| 121 | **[Jump Game II](https://leetcode.com/problems/jump-game-ii/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, BFS | Finding the minimum jumps. Solved greedily or as BFS level order. | LC Top, NeetCode |
| 122 | **[Gas Station](https://leetcode.com/problems/gas-station/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy | Classic greedy problem — proving existence and finding a valid starting point. | LC Top, NeetCode |
| 123 | **[Partition Labels](https://leetcode.com/problems/partition-labels/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Two Pointers | Finding the smallest partitions such that each letter appears in at most one part. | LC Top, NeetCode |
| 124 | **[Hand of Straights](https://leetcode.com/problems/hand-of-straights/)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Hashing | Forming consecutive groups greedily using counts. | NeetCode |

---

*\*Source Hint: Indicates sources where this problem is frequently listed (LC Top = LeetCode Top Interview Questions, Blind 75, NeetCode 150). This is indicative, not exhaustive.*

---

## 🚀 Final Thoughts & Next Steps

1. **Understand the Core Concept** — Don't just memorize solutions. Understand *why* a particular approach works.
2. **Practice Variations** — Once you solve a problem, think about variations and follow-up questions.
3. **Time Yourself** — Simulate interview conditions. Can you solve medium problems within 20–30 minutes?
4. **Explain Your Thought Process** — Practice articulating your solution clearly, step-by-step.
5. **Review Regularly** — Spaced repetition helps solidify concepts.

Good luck with your preparation! You've got this! 🌟

---
