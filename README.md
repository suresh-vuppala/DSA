# DSA

---

## 📚 Table of Contents

1. [📝 Programming Essentials & Arrays](#-programming-essentials--arrays)
2. [🔀 Subarrays · Subsets · Subsequences · Bit Manipulation · Recursion · Backtracking](#-subarrays--subsets--subsequences--bit-manipulation--recursion--backtracking)
3. [🔃 Sorting Algorithms & Two Pointers](#-sorting-algorithms--two-pointers)
4. [🔍 Searching Algorithms & Binary Search](#-searching-algorithms--binary-search)
5. [📐 Essential Math](#-essential-math)
6. [🎮 Game Theory](#-game-theory)
7. [🔐 Hashing](#-hashing)
8. [🖼️ Sliding Window, Strings & Rolling Hash](#️-sliding-window-strings--rolling-hash)
9. [📊 Prefix Sum](#-prefix-sum)
10. [🥞 Stack, Queue & Deque](#-stack-queue--deque)
11. [⛓️ Linked Lists](#️-linked-lists)
12. [🌳 Trees & Binary Search Trees](#-trees--binary-search-trees)
13. [🌲 Advanced Tree Problems](#-advanced-tree-problems)
14. [� Trie (Prefix Tree)](#-trie-prefix-tree)
15. [🔺 Heaps & Priority Queue](#-heaps--priority-queue)
16. [💡 Greedy](#-greedy)
17. [💻 Dynamic Programming](#-dynamic-programming)
18. [🧱 Advanced DP & Graph Introduction](#-advanced-dp--graph-introduction)
19. [🌐 Graph Algorithms](#-graph-algorithms)

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
| 1   | ⭐ **Two Sum** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing | The quintessential hash map problem. Checks basic data structure usage. | LC Top, Blind 75 | LC[https://leetcode.com/problems/two-sum/] |
| 2   | **Contains Duplicate** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing, Set | Basic set usage for uniqueness checks. | LC Top | LC[https://leetcode.com/problems/contains-duplicate/] 
| 3   | ⭐ **Best Time to Buy and Sell Stock** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Greedy, One Pass | Simple optimization — finding min/max efficiently in one pass. | LC Top, Blind 75 | LC[https://leetcode.com/problems/best-time-to-buy-and-sell-stock/] |
| 4   | ⭐ **Maximum Subarray** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Kadane's Algo, DP | The most famous DP intro problem (can be solved greedily). Fundamental pattern. | LC Top, Blind 75 | LC[https://leetcode.com/problems/maximum-subarray/] |
| 5   | ⭐ **Product of Array Except Self** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix/Suffix Products | Clever array manipulation without division. Tests thinking outside the box. | LC Top, Blind 75 | LC[https://leetcode.com/problems/product-of-array-except-self/] |
| 6   | **Maximum Product Subarray** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, Array Traversal | Variation of Max Subarray — handles negatives. Tests edge cases. | LC Top, Blind 75 | LC[https://leetcode.com/problems/maximum-product-subarray/] 
| 7   | **Next Permutation** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Array Manipulation | Understanding lexicographical order and in-place swaps. | LC Top | LC[https://leetcode.com/problems/next-permutation/] 
| 8   | **Find the Duplicate Number** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Cycle Detection (Floyd's) | Maps array problem to linked list cycle detection. Clever and efficient. | LC Top | LC[https://leetcode.com/problems/find-the-duplicate-number/] 

---

## 🔀 Subarrays · Subsets · Subsequences · Bit Manipulation · Recursion · Backtracking

> **Focus:** Understanding Subarrays vs Subsets vs Subsequences · Bit tricks · Recursive thinking · Backtracking template

### 📐 Math & Bit Manipulation

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 9   | **Number of 1 Bits** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation | Basic bit counting (Hamming weight). | LC Top, Blind 75 | LC[https://leetcode.com/problems/number-of-1-bits/] 
| 10  | **Counting Bits** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation, DP | Calculating bits for 0 to n efficiently using DP relation. | LC Top, Blind 75 | LC[https://leetcode.com/problems/counting-bits/] 
| 11  | **Reverse Bits** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation | Reversing bits of an integer. Tests careful bit shifting and masking. | LC Top, Blind 75 | LC[https://leetcode.com/problems/reverse-bits/] 
| 12  | **Missing Number** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation (XOR), Math | Finding the missing number using XOR properties or sum formula. | LC Top, Blind 75 | LC[https://leetcode.com/problems/missing-number/] 
| 13  | ⭐ **Sum of Two Integers** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Bit Manipulation | Adding numbers without `+` or `-`. Tests understanding of bitwise addition. | LC Top, Blind 75 | LC[https://leetcode.com/problems/sum-of-two-integers/] |

### 🔙 Backtracking

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 14  | ⭐ **Subsets** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Generating all possible combinations (powerset). Foundational backtracking. | LC Top, Blind 75 | LC[https://leetcode.com/problems/subsets/] |
| 15  | **Subsets II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Sorting | Subsets with duplicate elements. Requires careful duplicate handling. | LC Top, NeetCode | LC[https://leetcode.com/problems/subsets-ii/] 
| 16  | **Combination Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Finding combinations that sum to a target (with repetition allowed). | LC Top, Blind 75 | LC[https://leetcode.com/problems/combination-sum/] 
| 17  | **Combination Sum II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Sorting | Combination sum with duplicates — ensures unique combinations. | LC Top, NeetCode | LC[https://leetcode.com/problems/combination-sum-ii/] 
| 18  | **Permutations** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Generating all orderings of elements. | LC Top, Blind 75 | LC[https://leetcode.com/problems/permutations/] 
| 19  | ⭐ **Word Search** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, DFS | Classic grid backtracking — searching for a word in a 2D board. | LC Top, Blind 75 | LC[https://leetcode.com/problems/word-search/] |
| 20  | **Letter Combinations of a Phone Number** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Mapping digits to letters and generating combinations. | LC Top, NeetCode | LC[https://leetcode.com/problems/letter-combinations-of-a-phone-number/] 
| 21  | **Palindrome Partitioning** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, DP | Partitioning a string into palindromic substrings. | LC Top, NeetCode | LC[https://leetcode.com/problems/palindrome-partitioning/] 
| 22  | **N-Queens** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Backtracking | Quintessential constraint satisfaction backtracking problem. | LC Top | LC[https://leetcode.com/problems/n-queens/] 

---

## 🔃 Sorting Algorithms & Two Pointers

> **Focus:** Bubble Sort · Insertion Sort · Selection Sort · Merge Sort & Applications · Introduction to Two Pointer Technique · Comparisons & Classifications

### ⚖️ Two Pointers

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 23  | ⭐ **3Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sorting, Two Pointers | Foundational k-sum problem. Tests handling duplicates and two-pointer technique. | LC Top, Blind 75 | LC[https://leetcode.com/problems/3sum/] |
| 24  | **Container With Most Water** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers | Classic two-pointer optimization problem. | LC Top, Blind 75 | LC[https://leetcode.com/problems/container-with-most-water/] 
| 25  | ⭐ **Valid Palindrome** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Two Pointers, String | Basic two-pointer technique for symmetry checks, ignoring non-alphanumerics. | LC Top, Blind 75 | LC[https://leetcode.com/problems/valid-palindrome/] |
| 26  | **Sort Colors** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers | Dutch National Flag problem. Efficient in-place partitioning. | LC Top | LC[https://leetcode.com/problems/sort-colors/] 
| 27  | **Trapping Rain Water** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Two Pointers, DP, Stack | Multiple solutions exist. Tests optimization and insights. | LC Top, NeetCode | LC[https://leetcode.com/problems/trapping-rain-water/] 

---

## 🔍 Searching Algorithms & Binary Search

> **Focus:** Linear Search · Binary Search · Applications of Binary Search · Binary Search the Answer

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 28  | ⭐ **Binary Search** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Binary Search | The core algorithm itself. Essential foundation. | LC Top | LC[https://leetcode.com/problems/binary-search/] |
| 29  | **Search a 2D Matrix** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Applying binary search on a conceptually flattened sorted 2D matrix. | LC Top, Blind 75 | LC[https://leetcode.com/problems/search-a-2d-matrix/] 
| 30  | **Find Minimum in Rotated Sorted Array** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Classic modified binary search on rotated arrays. | LC Top, Blind 75 | LC[https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/] 
| 31  | ⭐ **Search in Rotated Sorted Array** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Extends the above — requires careful boundary condition handling. | LC Top, Blind 75 | LC[https://leetcode.com/problems/search-in-rotated-sorted-array/] |
| 32  | **Koko Eating Bananas** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search on Answer | Searching for the minimum speed (the answer) within a possible range. | NeetCode | LC[https://leetcode.com/problems/koko-eating-bananas/] 
| 33  | **Time Based Key-Value Store** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Binary Search | Searching for a value based on timestamp. Requires binary search on timestamps. | LC Top, Blind 75 | LC[https://leetcode.com/problems/time-based-key-value-store/] 
| 34  | ⭐ **Median of Two Sorted Arrays** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Binary Search | Advanced binary search on partitions to find the median efficiently. | LC Top, Blind 75 | LC[https://leetcode.com/problems/median-of-two-sorted-arrays/] |

---

## 📐 Essential Math

> **Focus:** Prime Numbers · Sieve of Eratosthenes · Segmented Sieve · Modular Arithmetic · Matrix Math

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 35  | **Reverse Integer** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Math, Overflow Check | Reversing digits of an integer while handling potential overflow. | LC Top | LC[https://leetcode.com/problems/reverse-integer/] 
| 36  | **Pow(x, n)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Recursion, Math | Efficient exponentiation using recursion (exponentiation by squaring). | LC Top | LC[https://leetcode.com/problems/powx-n/] 
| 37  | **Rotate Image** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Math, Matrix | Rotating a matrix in-place. Tests index manipulation. | LC Top, NeetCode | LC[https://leetcode.com/problems/rotate-image/] 
| 38  | **Spiral Matrix** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Matrix Traversal | Traversing a matrix in a spiral pattern. Tests boundary and direction handling. | LC Top, NeetCode | LC[https://leetcode.com/problems/spiral-matrix/] 
| 39  | **Set Matrix Zeroes** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Matrix, Space Optimization | Setting rows/columns to zero efficiently, often using O(1) extra space. | LC Top, NeetCode | LC[https://leetcode.com/problems/set-matrix-zeroes/] 

## 🎮 Game Theory

> **Focus:** Classic two-player games, nim, coin-row problems, etc.  
> *Problems will be added here as we expand the curriculum.*

## 🔐 Hashing

> **Focus:** Hash tables, frequency counting, and derived keys

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 40  | ⭐ **Group Anagrams** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Sorting | Grouping items based on a derived key (sorted string or char count). | LC Top, Blind 75 | LC[https://leetcode.com/problems/group-anagrams/] |
| 41  | ⭐ **Top K Frequent Elements** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Heap, QuickSelect | Finding most frequent items efficiently. Tests Heap or QuickSelect usage. | LC Top, Blind 75 | LC[https://leetcode.com/problems/top-k-frequent-elements/] |

## 🖼️ Sliding Window, Strings & Rolling Hash

> **Focus:** Sliding Window Technique · Maximum Sum of K Consecutive Elements · String Problems · Rolling Hash · Substring Matching · Rabin-Karp · Longest Common Substring

### 🖼️ Sliding Window

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 42  | ⭐ **Longest Substring Without Repeating Characters** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | The canonical sliding window problem. Tests efficient substring analysis. | LC Top, Blind 75 | LC[https://leetcode.com/problems/longest-substring-without-repeating-characters/] |
| 43  | ⭐ **Longest Repeating Character Replacement** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | Advanced sliding window requiring careful window condition management. | LC Top, Blind 75 | LC[https://leetcode.com/problems/longest-repeating-character-replacement/] |
| 44  | **Permutation in String** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | Fixed-size window check using frequency maps. | LC Top, Blind 75 | LC[https://leetcode.com/problems/permutation-in-string/] 
| 45  | ⭐ **Minimum Window Substring** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Sliding Window, Hashing | The definitive challenging sliding window problem. Tests complex state tracking. | LC Top, Blind 75 | LC[https://leetcode.com/problems/minimum-window-substring/] |

### ✍️ Strings

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 46  | ⭐ **Valid Anagram** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing, Sorting | Fundamental check for character counts. Basic but essential. | LC Top, Blind 75 | LC[https://leetcode.com/problems/valid-anagram/] |
| 47  | ⭐ **Valid Parentheses** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Stack | Classic stack application for matching pairs. | LC Top, Blind 75 | LC[https://leetcode.com/problems/valid-parentheses/] |
| 48  | ⭐ **Longest Palindromic Substring** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Expand Around Center, DP | Finding optimal substructures. Expand-around-center is often preferred. | LC Top, Blind 75 | LC[https://leetcode.com/problems/longest-palindromic-substring/] |
| 49  | **Palindromic Substrings** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Expand Around Center, DP | Counting all palindromic substrings. Similar logic to above but counting. | LC Top, Blind 75 | LC[https://leetcode.com/problems/palindromic-substrings/] 
| 50  | **Encode and Decode Strings** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | String Design, Delimiter | Practical problem often asked in system design contexts. Tests edge cases. | Blind 75, NeetCode | LC[https://leetcode.com/problems/encode-and-decode-strings/] 

---

## 📊 Prefix Sum

> **Focus:** Prefix Sum / Cumulative Sum · Range Sum Queries · Subarray Sum Problems · 2D Prefix Sum

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 51  | ⭐ **Range Sum Query - Immutable** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Prefix Sum | The canonical prefix sum problem. Foundation for range queries. | LC Top | LC[https://leetcode.com/problems/range-sum-query-immutable/] |
| 52  | **Subarray Sum Equals K** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Hashing | Finding subarrays with target sum efficiently using prefix sums. | LC Top, NeetCode | LC[https://leetcode.com/problems/subarray-sum-equals-k/] 
| 53  | **Continuous Subarray Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Modulo | Range sum with modular arithmetic constraint. Tests prefix sum insights. | LC Top, NeetCode | LC[https://leetcode.com/problems/continuous-subarray-sum/] 
| 54  | **2D Range Sum Query - Immutable** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | 2D Prefix Sum | Extending prefix sum to 2D grids for efficient area queries. | LC Top | LC[https://leetcode.com/problems/range-sum-query-2d-immutable/] 
| 55  | **Longest Well-Performing Interval** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Hashing | Converting problem to finding longest subarray with sum > 0. | LC Top, NeetCode | LC[https://leetcode.com/problems/longest-well-performing-interval/] 
| 56  | ⭐ **Longest Balanced Substring II** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Prefix Sum, String | Advanced string balancing problem solved efficiently using prefix sum patterns. | LC Top | LC[https://leetcode.com/problems/longest-balanced-substring-ii/] |

---

## 🥞 Stack, Queue & Deque

> **Focus:** Stack · Queue · Deque · Circular Queue · Monotonic Stack patterns

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 57  | **Min Stack** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Stack Design | Designing a stack with O(1) min retrieval. Tests data structure design. | LC Top, NeetCode | LC[https://leetcode.com/problems/min-stack/] 
| 58  | **Evaluate Reverse Polish Notation** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Stack | Direct stack application for expression evaluation. | LC Top | LC[https://leetcode.com/problems/evaluate-reverse-polish-notation/] 
| 59  | **Daily Temperatures** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Monotonic Stack | Classic "next greater element" pattern using a monotonic stack. | LC Top, NeetCode | LC[https://leetcode.com/problems/daily-temperatures/] 
| 60  | **Largest Rectangle in Histogram** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Monotonic Stack | Challenging application of monotonic stack for area calculation. | LC Top, NeetCode | LC[https://leetcode.com/problems/largest-rectangle-in-histogram/] 

---

## ⛓️ Linked Lists

> **Focus:** Linked List operations · Classic Linked List Problems

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 61  | ⭐ **Reverse Linked List** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Iteration, Recursion | The absolute fundamental linked list manipulation. | LC Top, Blind 75 | LC[https://leetcode.com/problems/reverse-linked-list/] |
| 62  | ⭐ **Linked List Cycle** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Floyd's Cycle Detection | Classic application of the Tortoise and Hare algorithm. | LC Top, Blind 75 | LC[https://leetcode.com/problems/linked-list-cycle/] |
| 63  | ⭐ **Merge Two Sorted Lists** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Pointers, Iteration | Foundational merging logic, basis for Merge Sort. | LC Top, Blind 75 | LC[https://leetcode.com/problems/merge-two-sorted-lists/] |
| 64  | **Remove Nth Node From End of List** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers (Fast/Slow) | Common two-pointer pattern for finding elements relative to the end. | LC Top, Blind 75 | LC[https://leetcode.com/problems/remove-nth-node-from-end-of-list/] 
| 65  | **Reorder List** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Find Middle, Reverse, Merge | Combines multiple core list operations. Good test of modular thinking. | LC Top, Blind 75 | LC[https://leetcode.com/problems/reorder-list/] 
| 66  | ⭐ **Merge k Sorted Lists** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Heap (Priority Queue), D&C | Scalable merging. Tests heap usage or divide-and-conquer approach. | LC Top, Blind 75 | LC[https://leetcode.com/problems/merge-k-sorted-lists/] |

---

## 🌳 Trees & Binary Search Trees

> **Focus:** Tree Traversals (Inorder, Preorder, Postorder) · BFS / DFS · Standard Tree Problems · BST Insert / Search / Delete · Recursive & Iterative Traversals

### 🌳 Tree Traversal & BFS/DFS

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 67  | ⭐ **Maximum Depth of Binary Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Basic recursive tree traversal. | LC Top, Blind 75 | LC[https://leetcode.com/problems/maximum-depth-of-binary-tree/] |
| 68  | ⭐ **Same Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Basic structural comparison using recursion. | LC Top, Blind 75 | LC[https://leetcode.com/problems/same-tree/] |
| 69  | ⭐ **Invert Binary Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS/BFS, Recursion | Famous, simple tree manipulation via recursion or iteration. | LC Top, Blind 75 | LC[https://leetcode.com/problems/invert-binary-tree/] |
| 70  | **Subtree of Another Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Recursive check involving a helper for subtree matching. | LC Top, Blind 75 | LC[https://leetcode.com/problems/subtree-of-another-tree/] 
| 71  | **Diameter of Binary Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Calculating longest path via recursive depth calculation. | LC Top, NeetCode | LC[https://leetcode.com/problems/diameter-of-binary-tree/] 
| 72  | ⭐ **Binary Tree Level Order Traversal** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS, Queue | The canonical BFS application on trees. | LC Top, Blind 75 | LC[https://leetcode.com/problems/binary-tree-level-order-traversal/] |
| 73  | **Binary Tree Right Side View** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS, DFS | Variation of level order traversal (finding the last node at each level). | LC Top, NeetCode | LC[https://leetcode.com/problems/binary-tree-right-side-view/] 

### 🌲 Binary Search Trees

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 74  | ⭐ **Validate Binary Search Tree** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DFS, Recursion, Range | Checking BST validity requires passing down min/max constraints. | LC Top, Blind 75 | LC[https://leetcode.com/problems/validate-binary-search-tree/] |
| 75  | ⭐ **Kth Smallest Element in a BST** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Inorder Traversal, DFS | Leverages the inorder traversal property of BSTs. | LC Top, Blind 75 | LC[https://leetcode.com/problems/kth-smallest-element-in-a-bst/] |
| 76  | ⭐ **Lowest Common Ancestor of a BST** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BST Properties, DFS | Utilizes BST properties for efficient LCA finding. | LC Top, Blind 75 | LC[https://leetcode.com/problems/lowest-common-ancestor-of-a-bst/] |

---

## 🌲 Advanced Tree Problems

> **Focus:** Advanced Trees · Complex recursive patterns · Tree construction & serialization

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 77  | **Construct Binary Tree from Preorder and Inorder Traversal** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Recursion, Hashing | Classic tree construction problem using traversal properties. | LC Top, Blind 75 | LC[https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/] 
| 78  | ⭐ **Binary Tree Maximum Path Sum** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DFS, Recursion | Tricky recursion where path can start/end anywhere. Requires careful state return. | LC Top, Blind 75 | LC[https://leetcode.com/problems/binary-tree-maximum-path-sum/] |
| 79  | **Serialize and Deserialize Binary Tree** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DFS/BFS, String | Design problem involving tree representation as a string. | LC Top, Blind 75 | LC[https://leetcode.com/problems/serialize-and-deserialize-binary-tree/] 

---

## 🔎 Trie (Prefix Tree)

> **Focus:** Trie Data Structure · Prefix-based Searching · Dictionary Problems · Autocomplete & Word Games

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 80  | ⭐ **Implement Trie (Prefix Tree)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, Design | Foundational data structure for string/dictionary problems. | LC Top, Blind 75 | LC[https://leetcode.com/problems/implement-trie-prefix-tree/] |
| 81  | **Design Add and Search Words Data Structure** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, DFS, Backtracking | Extends Trie with wildcard search. Tests recursive search logic. | LC Top, Blind 75 | LC[https://leetcode.com/problems/design-add-and-search-words-data-structure/] 
| 82  | **Word Search II** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Trie, Backtracking, DFS | Combines Trie efficiency with grid backtracking. Highly practical. | LC Top, Blind 75 | LC[https://leetcode.com/problems/word-search-ii/] 
| 83  | **Prefix and Suffix Search** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Trie, Design | Designing a structure for efficient prefix/suffix queries on words. | NeetCode | LC[https://leetcode.com/problems/prefix-and-suffix-search/] 
| 84  | **Replace Words** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, String | Using Trie to find shortest matching prefix efficiently. | LC Top, NeetCode | LC[https://leetcode.com/problems/replace-words/] 
| 85  | **Stream of Characters** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Trie, Stream Processing | Matching words in a stream using Trie with suffix tracking. | NeetCode | LC[https://leetcode.com/problems/stream-of-characters/] 

---

## 🔺 Heaps & Priority Queue

> **Focus:** Min/Max Heap · Heap Sort · Classic Heap Problems

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 86  | **Kth Largest Element in an Array** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Heap, QuickSelect | Finding the specific Kth element efficiently. | LC Top, NeetCode | LC[https://leetcode.com/problems/kth-largest-element-in-an-array/] 
| 87  | **Task Scheduler** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Heap, Hashing | Scheduling tasks with cooldowns — solved greedily or with a max-heap. | LC Top, NeetCode | LC[https://leetcode.com/problems/task-scheduler/] 
| 88  | **Find Median from Data Stream** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Two Heaps (Max/Min) | Classic design problem using two heaps to maintain median in streaming fashion. | LC Top, Blind 75 | LC[https://leetcode.com/problems/find-median-from-data-stream/] 

---

## 💡 Greedy

> **Focus:** Greedy Paradigm · Making Locally Optimal Choices · Classic Greedy Problems · Practical Applications

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 89  | **Jump Game** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy | Checking reachability by tracking the maximum reachable index greedily. | LC Top, Blind 75 | LC[https://leetcode.com/problems/jump-game/] 
| 90  | **Jump Game II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, BFS | Finding the minimum jumps. Solved greedily or as BFS level order. | LC Top, NeetCode | LC[https://leetcode.com/problems/jump-game-ii/] 
| 91  | **Gas Station** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy | Classic greedy problem — proving existence and finding a valid starting point. | LC Top, NeetCode | LC[https://leetcode.com/problems/gas-station/] 
| 92  | **Partition Labels** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Two Pointers | Finding the smallest partitions such that each letter appears in at most one part. | LC Top, NeetCode | LC[https://leetcode.com/problems/partition-labels/] 
| 93  | **Hand of Straights** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Hashing | Forming consecutive groups greedily using counts. | NeetCode | LC[https://leetcode.com/problems/hand-of-straights/] 
| 94  | **Interval Scheduling Maximization** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Sorting | Maximizing event attendance using greedy interval selection. | LC Top, NeetCode | LC[https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/] 

---

## 💻 Dynamic Programming

> **Focus:** Nth Fibonacci Number · Memoization · Tabulation · Classic DP Problems

### 💻 1D Dynamic Programming

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 95  | ⭐ **Climbing Stairs** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DP (Fibonacci) | The introductory DP problem, equivalent to Fibonacci sequence. | LC Top, Blind 75 | LC[https://leetcode.com/problems/climbing-stairs/] |
| 96  | ⭐ **Coin Change** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Unbounded Knapsack) | Classic DP for minimum coins. Tests state definition and transitions. | LC Top, Blind 75 | LC[https://leetcode.com/problems/coin-change/] |
| 97  | ⭐ **Longest Increasing Subsequence** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, Binary Search | Fundamental subsequence problem. Can be optimized with Binary Search. | LC Top, Blind 75 | LC[https://leetcode.com/problems/longest-increasing-subsequence/] |
| 98  | ⭐ **Word Break** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, String | Checking if a string can be segmented using a dictionary. Common string DP. | LC Top, Blind 75 | LC[https://leetcode.com/problems/word-break/] |
| 99  | ⭐ **House Robber** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP | Simple 1D DP with non-adjacent constraint. | LC Top, Blind 75 | LC[https://leetcode.com/problems/house-robber/] |
| 100 | **House Robber II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP | Circular variation of House Robber. Tests reducing to subproblems. | LC Top, Blind 75 | LC[https://leetcode.com/problems/house-robber-ii/] 
| 101 | **Decode Ways** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, String | Counting ways to decode a numeric string. Tests handling DP states carefully. | LC Top, Blind 75 | LC[https://leetcode.com/problems/decode-ways/] 
| 102 | **Partition Equal Subset Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (0/1 Knapsack) | Subset sum variation. Tests boolean DP state. | LC Top, NeetCode | LC[https://leetcode.com/problems/partition-equal-subset-sum/] 

### 🧱 2D & Advanced Dynamic Programming

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 94  | **Unique Paths** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Grid) | Basic 2D DP on a grid. Calculating paths from top-left to bottom-right. | LC Top, Blind 75 | LC[https://leetcode.com/problems/unique-paths/] 
| 95  | **Longest Common Subsequence** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (2D String) | Fundamental DP for comparing two sequences. | LC Top, Blind 75 | LC[https://leetcode.com/problems/longest-common-subsequence/] 
| 96  | **Edit Distance** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (2D String) | Classic DP for string transformation distance (Levenshtein). | LC Top, NeetCode | LC[https://leetcode.com/problems/edit-distance/] 
| 97  | **Maximal Square** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Grid) | Finding the largest square of 1s in a binary matrix. | LC Top | LC[https://leetcode.com/problems/maximal-square/] 
| 98  | **Best Time to Buy and Sell Stock with Cooldown** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (State Machine) | Stock problem requiring state machine DP (buy, sell, cooldown). | LC Top, NeetCode | LC[https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/] |
| 99  | **Burst Balloons** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DP (Interval) | Challenging interval DP. Requires thinking about the last operation. | LC Top, NeetCode | LC[https://leetcode.com/problems/burst-balloons/] 
| 100 | **Regular Expression Matching** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DP, Recursion | Complex DP with `'.'` and `'*'`. Tests careful state transitions. | LC Top | LC[https://leetcode.com/problems/regular-expression-matching/] 

---

## 🧱 Advanced DP

> **Focus:** Advanced DP Problems

### 🧩 Intervals (Advanced DP adjacent)

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 101 | ⭐ **Insert Interval** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Interval Merging | Inserting a new interval into sorted, non-overlapping intervals and merging. | LC Top, Blind 75 | LC[https://leetcode.com/problems/insert-interval/] |
| 102 | ⭐ **Merge Intervals** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sorting, Intervals | The canonical interval merging problem after sorting by start time. | LC Top, Blind 75 | LC[https://leetcode.com/problems/merge-intervals/] |
| 103 | ⭐ **Non-overlapping Intervals** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Sorting | Finding minimum removals to make intervals non-overlapping. | LC Top, Blind 75 | LC[https://leetcode.com/problems/non-overlapping-intervals/] |
| 104 | **Meeting Rooms** *(Premium)* | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Sorting, Intervals | Checking if a person can attend all meetings (no overlaps). | Blind 75, NeetCode | LC[https://leetcode.com/problems/meeting-rooms/] 
| 105 | ⭐ **Meeting Rooms II** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Heap, Sorting | Finding the minimum number of rooms required. | Blind 75, NeetCode | LC[https://leetcode.com/problems/meeting-rooms-ii/] |
| 106 | **Minimum Interval to Include Each Query** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Heap, Sorting, Sweep Line | Advanced interval querying using heaps and sorting. | NeetCode | LC[https://leetcode.com/problems/minimum-interval-to-include-each-query/] 

---

## 🌐 Graph Algorithms

> **Focus:** Graph Traversals (BFS & DFS) · Dijkstra's Algorithm · Topological Sorting · Bipartite Graphs · Kruskal's Algorithm · Union-Find

### Graph BFS / DFS

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 107 | ⭐ **Number of Islands** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Grid | The fundamental graph traversal problem on a grid. Counts connected components. | LC Top, Blind 75 | LC[https://leetcode.com/problems/number-of-islands/] |
| 108 | ⭐ **Clone Graph** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Hashing | Deep copying graph structure. Tests handling visited nodes. | LC Top, Blind 75 | LC[https://leetcode.com/problems/clone-graph/] |
| 109 | **Pacific Atlantic Water Flow** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Grid | Multi-source traversal from oceans inward. Tests simultaneous graph traversals. | LC Top, Blind 75 | LC[https://leetcode.com/problems/pacific-atlantic-water-flow/] 

### Dijkstra's Algorithm (Shortest Path)

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 110 | **Network Delay Time** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Dijkstra's/Bellman-Ford | Shortest path from a source in a weighted directed graph. | LC Top, NeetCode | LC[https://leetcode.com/problems/network-delay-time/] 
| 111 | **Cheapest Flights Within K Stops** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Bellman-Ford / Modified Dijkstra | Shortest path with constraint on number of edges. | NeetCode | LC[https://leetcode.com/problems/cheapest-flights-within-k-stops/] 
| 112 | ⭐ **Word Ladder** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | BFS, Implicit Graph | Shortest path on an implicit graph where edges are word transformations. | LC Top, Blind 75 | LC[https://leetcode.com/problems/word-ladder/] |

### Topological Sorting & Bipartite Graphs

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 113 | ⭐ **Course Schedule** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Topological Sort (DFS/BFS) | Detecting cycles in a directed graph (prerequisite check). Essential pattern. | LC Top, Blind 75 | LC[https://leetcode.com/problems/course-schedule/] |
| 114 | **Course Schedule II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Topological Sort | Finding a valid course order. Extends Course Schedule I. | LC Top, NeetCode | LC[https://leetcode.com/problems/course-schedule-ii/] 
| 115 | **Alien Dictionary** *(Premium)* | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Topological Sort, Graph Building | Deriving character order from a sorted word list. Complex graph construction. | Blind 75, NeetCode | LC[https://leetcode.com/problems/alien-dictionary/] 

### Union-Find (Kruskal's / Connectivity)

| #   | Problem | Difficulty | Concepts | Why MAANG+ Loves It | Source Hint* |
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 116 | **Redundant Connection** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find | Finding the edge that creates a cycle. Classic Union-Find application. | NeetCode | LC[https://leetcode.com/problems/redundant-connection/] 
| 117 | **Number of Connected Components** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find, BFS/DFS | Basic connectivity check using Union-Find. | Blind 75, NeetCode | LC[https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/] 
| 118 | **Graph Valid Tree** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find, BFS/DFS | Checking if a graph is a tree (connected and acyclic). | Blind 75, NeetCode | LC[https://leetcode.com/problems/graph-valid-tree/] 
| 119 | **Critical Connections in a Network** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Tarjan's Algorithm (Bridges) | Finding bridges in a graph. Tests understanding of advanced graph algorithms. | NeetCode | LC[https://leetcode.com/problems/critical-connections-in-a-network/] 

---


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
