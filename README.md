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

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 1   | ⭐ **Two Sum** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing | The quintessential hash map problem. Checks basic data structure usage. | [LC](https://leetcode.com/problems/two-sum/), Blind 75
| 2   | **Contains Duplicate** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing, Set | Basic set usage for uniqueness checks. | [LC](https://leetcode.com/problems/contains-duplicate/)
| 3   | ⭐ **Best Time to Buy and Sell Stock** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Greedy, One Pass | Simple optimization — finding min/max efficiently in one pass. | [LC](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/), Blind 75
| 4   | ⭐ **Maximum Subarray** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Kadane's Algo, DP | The most famous DP intro problem (can be solved greedily). Fundamental pattern. | [LC](https://leetcode.com/problems/maximum-subarray/), Blind 75
| 5   | ⭐ **Product of Array Except Self** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix/Suffix Products | Clever array manipulation without division. Tests thinking outside the box. | [LC](https://leetcode.com/problems/product-of-array-except-self/), Blind 75
| 6   | **Maximum Product Subarray** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, Array Traversal | Variation of Max Subarray — handles negatives. Tests edge cases. | [LC](https://leetcode.com/problems/maximum-product-subarray/), Blind 75
| 7   | **Next Permutation** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Array Manipulation | Understanding lexicographical order and in-place swaps. | [LC](https://leetcode.com/problems/next-permutation/)
| 8   | **Find the Duplicate Number** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Cycle Detection (Floyd's) | Maps array problem to linked list cycle detection. Clever and efficient. | [LC](https://leetcode.com/problems/find-the-duplicate-number/)

---

## 🔀 Subarrays · Subsets · Subsequences · Bit Manipulation · Recursion · Backtracking

> **Focus:** Understanding Subarrays vs Subsets vs Subsequences · Bit tricks · Recursive thinking · Backtracking template

### 📐 Math & Bit Manipulation

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 9   | **Number of 1 Bits** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation | Basic bit counting (Hamming weight). | [LC](https://leetcode.com/problems/number-of-1-bits/), Blind 75
| 10  | **Counting Bits** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation, DP | Calculating bits for 0 to n efficiently using DP relation. | [LC](https://leetcode.com/problems/counting-bits/), Blind 75
| 11  | **Reverse Bits** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation | Reversing bits of an integer. Tests careful bit shifting and masking. | [LC](https://leetcode.com/problems/reverse-bits/), Blind 75
| 12  | **Missing Number** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Bit Manipulation (XOR), Math | Finding the missing number using XOR properties or sum formula. | [LC](https://leetcode.com/problems/missing-number/), Blind 75
| 13  | ⭐ **Sum of Two Integers** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Bit Manipulation | Adding numbers without `+` or `-`. Tests understanding of bitwise addition. | [LC](https://leetcode.com/problems/sum-of-two-integers/), Blind 75

### 🔙 Backtracking

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 14  | ⭐ **Subsets** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Generating all possible combinations (powerset). Foundational backtracking. | [LC](https://leetcode.com/problems/subsets/), Blind 75
| 15  | **Subsets II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Sorting | Subsets with duplicate elements. Requires careful duplicate handling. | [LC](https://leetcode.com/problems/subsets-ii/), NeetCode
| 16  | **Combination Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Finding combinations that sum to a target (with repetition allowed). | [LC](https://leetcode.com/problems/combination-sum/), Blind 75
| 17  | **Combination Sum II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Sorting | Combination sum with duplicates — ensures unique combinations. | [LC](https://leetcode.com/problems/combination-sum-ii/), NeetCode
| 18  | **Permutations** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Generating all orderings of elements. | [LC](https://leetcode.com/problems/permutations/), Blind 75
| 19  | ⭐ **Word Search** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, DFS | Classic grid backtracking — searching for a word in a 2D board. | [LC](https://leetcode.com/problems/word-search/), Blind 75
| 20  | **Letter Combinations of a Phone Number** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, Recursion | Mapping digits to letters and generating combinations. | [LC](https://leetcode.com/problems/letter-combinations-of-a-phone-number/), NeetCode
| 21  | **Palindrome Partitioning** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Backtracking, DP | Partitioning a string into palindromic substrings. | [LC](https://leetcode.com/problems/palindrome-partitioning/), NeetCode
| 22  | **N-Queens** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Backtracking | Quintessential constraint satisfaction backtracking problem. | [LC](https://leetcode.com/problems/n-queens/)

---

## 🔃 Sorting Algorithms & Two Pointers

> **Focus:** Bubble Sort · Insertion Sort · Selection Sort · Merge Sort & Applications · Introduction to Two Pointer Technique · Comparisons & Classifications

### ⚖️ Two Pointers

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 23  | ⭐ **3Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sorting, Two Pointers | Foundational k-sum problem. Tests handling duplicates and two-pointer technique. | [LC](https://leetcode.com/problems/3sum/), Blind 75
| 24  | **Container With Most Water** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers | Classic two-pointer optimization problem. | [LC](https://leetcode.com/problems/container-with-most-water/), Blind 75
| 25  | ⭐ **Valid Palindrome** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Two Pointers, String | Basic two-pointer technique for symmetry checks, ignoring non-alphanumerics. | [LC](https://leetcode.com/problems/valid-palindrome/), Blind 75
| 26  | **Sort Colors** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers | Dutch National Flag problem. Efficient in-place partitioning. | [LC](https://leetcode.com/problems/sort-colors/)
| 27  | **Trapping Rain Water** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Two Pointers, DP, Stack | Multiple solutions exist. Tests optimization and insights. | [LC](https://leetcode.com/problems/trapping-rain-water/), NeetCode

---

## 🔍 Searching Algorithms & Binary Search

> **Focus:** Linear Search · Binary Search · Applications of Binary Search · Binary Search the Answer

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 28  | ⭐ **Binary Search** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Binary Search | The core algorithm itself. Essential foundation. | [LC](https://leetcode.com/problems/binary-search/)
| 29  | **Search a 2D Matrix** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Applying binary search on a conceptually flattened sorted 2D matrix. | [LC](https://leetcode.com/problems/search-a-2d-matrix/), Blind 75
| 30  | **Find Minimum in Rotated Sorted Array** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Classic modified binary search on rotated arrays. | [LC](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/), Blind 75
| 31  | ⭐ **Search in Rotated Sorted Array** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search | Extends the above — requires careful boundary condition handling. | [LC](https://leetcode.com/problems/search-in-rotated-sorted-array/), Blind 75
| 32  | **Koko Eating Bananas** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Binary Search on Answer | Searching for the minimum speed (the answer) within a possible range. | [NeetCode](https://leetcode.com/problems/koko-eating-bananas/)
| 33  | **Time Based Key-Value Store** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Binary Search | Searching for a value based on timestamp. Requires binary search on timestamps. | [LC](https://leetcode.com/problems/time-based-key-value-store/), Blind 75
| 34  | ⭐ **Median of Two Sorted Arrays** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Binary Search | Advanced binary search on partitions to find the median efficiently. | [LC](https://leetcode.com/problems/median-of-two-sorted-arrays/), Blind 75

---

## 📐 Essential Math

> **Focus:** Prime Numbers · Sieve of Eratosthenes · Segmented Sieve · Modular Arithmetic · Matrix Math

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 35  | **Reverse Integer** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Math, Overflow Check | Reversing digits of an integer while handling potential overflow. | [LC](https://leetcode.com/problems/reverse-integer/)
| 36  | **Pow(x, n)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Recursion, Math | Efficient exponentiation using recursion (exponentiation by squaring). | [LC](https://leetcode.com/problems/powx-n/)
| 37  | **Rotate Image** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Math, Matrix | Rotating a matrix in-place. Tests index manipulation. | [LC](https://leetcode.com/problems/rotate-image/), NeetCode
| 38  | **Spiral Matrix** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Matrix Traversal | Traversing a matrix in a spiral pattern. Tests boundary and direction handling. | [LC](https://leetcode.com/problems/spiral-matrix/), NeetCode
| 39  | **Set Matrix Zeroes** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Matrix, Space Optimization | Setting rows/columns to zero efficiently, often using O(1) extra space. | [LC](https://leetcode.com/problems/set-matrix-zeroes/), NeetCode

## 🎮 Game Theory

> **Focus:** Classic two-player games, nim, coin-row problems, etc.
> *Problems will be added here as we expand the curriculum.*

## 🔐 Hashing

> **Focus:** Hash tables, frequency counting, and derived keys

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 40  | ⭐ **Group Anagrams** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Sorting | Grouping items based on a derived key (sorted string or char count). | [LC](https://leetcode.com/problems/group-anagrams/), Blind 75
| 41  | ⭐ **Top K Frequent Elements** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Hashing, Heap, QuickSelect | Finding most frequent items efficiently. Tests Heap or QuickSelect usage. | [LC](https://leetcode.com/problems/top-k-frequent-elements/), Blind 75

## 🖼️ Sliding Window, Strings & Rolling Hash

> **Focus:** Sliding Window Technique · Maximum Sum of K Consecutive Elements · String Problems · Rolling Hash · Substring Matching · Rabin-Karp · Longest Common Substring

### 🖼️ Sliding Window

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 42  | ⭐ **Longest Substring Without Repeating Characters** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | The canonical sliding window problem. Tests efficient substring analysis. | [LC](https://leetcode.com/problems/longest-substring-without-repeating-characters/), Blind 75
| 43  | ⭐ **Longest Repeating Character Replacement** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | Advanced sliding window requiring careful window condition management. | [LC](https://leetcode.com/problems/longest-repeating-character-replacement/), Blind 75
| 44  | **Permutation in String** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sliding Window, Hashing | Fixed-size window check using frequency maps. | [LC](https://leetcode.com/problems/permutation-in-string/), Blind 75
| 45  | ⭐ **Minimum Window Substring** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Sliding Window, Hashing | The definitive challenging sliding window problem. Tests complex state tracking. | [LC](https://leetcode.com/problems/minimum-window-substring/), Blind 75

### ✍️ Strings

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 46  | ⭐ **Valid Anagram** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Hashing, Sorting | Fundamental check for character counts. Basic but essential. | [LC](https://leetcode.com/problems/valid-anagram/), Blind 75
| 47  | ⭐ **Valid Parentheses** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Stack | Classic stack application for matching pairs. | [LC](https://leetcode.com/problems/valid-parentheses/), Blind 75
| 48  | ⭐ **Longest Palindromic Substring** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Expand Around Center, DP | Finding optimal substructures. Expand-around-center is often preferred. | [LC](https://leetcode.com/problems/longest-palindromic-substring/), Blind 75
| 49  | **Palindromic Substrings** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Expand Around Center, DP | Counting all palindromic substrings. Similar logic to above but counting. | [LC](https://leetcode.com/problems/palindromic-substrings/), Blind 75
| 50  | **Encode and Decode Strings** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | String Design, Delimiter | Practical problem often asked in system design contexts. Tests edge cases. | Blind 75, [NeetCode](https://leetcode.com/problems/encode-and-decode-strings/)

---

## 📊 Prefix Sum

> **Focus:** Prefix Sum / Cumulative Sum · Range Sum Queries · Subarray Sum Problems · 2D Prefix Sum

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 51  | ⭐ **Range Sum Query - Immutable** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Prefix Sum | The canonical prefix sum problem. Foundation for range queries. | [LC](https://leetcode.com/problems/range-sum-query-immutable/)
| 52  | **Subarray Sum Equals K** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Hashing | Finding subarrays with target sum efficiently using prefix sums. | [LC](https://leetcode.com/problems/subarray-sum-equals-k/), NeetCode
| 53  | **Continuous Subarray Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Modulo | Range sum with modular arithmetic constraint. Tests prefix sum insights. | [LC](https://leetcode.com/problems/continuous-subarray-sum/), NeetCode
| 54  | **2D Range Sum Query - Immutable** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | 2D Prefix Sum | Extending prefix sum to 2D grids for efficient area queries. | [LC](https://leetcode.com/problems/range-sum-query-2d-immutable/)
| 55  | **Longest Well-Performing Interval** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Prefix Sum, Hashing | Converting problem to finding longest subarray with sum > 0. | [LC](https://leetcode.com/problems/longest-well-performing-interval/), NeetCode
| 56  | ⭐ **Longest Balanced Substring II** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Prefix Sum, String | Advanced string balancing problem solved efficiently using prefix sum patterns. | [LC](https://leetcode.com/problems/longest-balanced-substring-ii/)

---

## 🥞 Stack, Queue & Deque

> **Focus:** Stack · Queue · Deque · Circular Queue · Monotonic Stack patterns

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 57  | **Min Stack** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Stack Design | Designing a stack with O(1) min retrieval. Tests data structure design. | [LC](https://leetcode.com/problems/min-stack/), NeetCode
| 58  | **Evaluate Reverse Polish Notation** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Stack | Direct stack application for expression evaluation. | [LC](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
| 59  | **Daily Temperatures** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Monotonic Stack | Classic "next greater element" pattern using a monotonic stack. | [LC](https://leetcode.com/problems/daily-temperatures/), NeetCode
| 60  | **Largest Rectangle in Histogram** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Monotonic Stack | Challenging application of monotonic stack for area calculation. | [LC](https://leetcode.com/problems/largest-rectangle-in-histogram/), NeetCode

---

## ⛓️ Linked Lists

> **Focus:** Linked List operations · Classic Linked List Problems

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 61  | ⭐ **Reverse Linked List** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Iteration, Recursion | The absolute fundamental linked list manipulation. | [LC](https://leetcode.com/problems/reverse-linked-list/), Blind 75
| 62  | ⭐ **Linked List Cycle** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Floyd's Cycle Detection | Classic application of the Tortoise and Hare algorithm. | [LC](https://leetcode.com/problems/linked-list-cycle/), Blind 75
| 63  | ⭐ **Merge Two Sorted Lists** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Pointers, Iteration | Foundational merging logic, basis for Merge Sort. | [LC](https://leetcode.com/problems/merge-two-sorted-lists/), Blind 75
| 64  | **Remove Nth Node From End of List** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Two Pointers (Fast/Slow) | Common two-pointer pattern for finding elements relative to the end. | [LC](https://leetcode.com/problems/remove-nth-node-from-end-of-list/), Blind 75
| 65  | **Reorder List** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Find Middle, Reverse, Merge | Combines multiple core list operations. Good test of modular thinking. | [LC](https://leetcode.com/problems/reorder-list/), Blind 75
| 66  | ⭐ **Merge k Sorted Lists** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Heap (Priority Queue), D&C | Scalable merging. Tests heap usage or divide-and-conquer approach. | [LC](https://leetcode.com/problems/merge-k-sorted-lists/), Blind 75

---

## 🌳 Trees & Binary Search Trees

> **Focus:** Tree Traversals (Inorder, Preorder, Postorder) · BFS / DFS · Standard Tree Problems · BST Insert / Search / Delete · Recursive & Iterative Traversals

### 🌳 Tree Traversal & BFS/DFS

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 67  | ⭐ **Maximum Depth of Binary Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Basic recursive tree traversal. | [LC](https://leetcode.com/problems/maximum-depth-of-binary-tree/), Blind 75
| 68  | ⭐ **Same Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Basic structural comparison using recursion. | [LC](https://leetcode.com/problems/same-tree/), Blind 75
| 69  | ⭐ **Invert Binary Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS/BFS, Recursion | Famous, simple tree manipulation via recursion or iteration. | [LC](https://leetcode.com/problems/invert-binary-tree/), Blind 75
| 70  | **Subtree of Another Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Recursive check involving a helper for subtree matching. | [LC](https://leetcode.com/problems/subtree-of-another-tree/), Blind 75
| 71  | **Diameter of Binary Tree** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DFS, Recursion | Calculating longest path via recursive depth calculation. | [LC](https://leetcode.com/problems/diameter-of-binary-tree/), NeetCode
| 72  | ⭐ **Binary Tree Level Order Traversal** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS, Queue | The canonical BFS application on trees. | [LC](https://leetcode.com/problems/binary-tree-level-order-traversal/), Blind 75
| 73  | **Binary Tree Right Side View** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS, DFS | Variation of level order traversal (finding the last node at each level). | [LC](https://leetcode.com/problems/binary-tree-right-side-view/), NeetCode

### 🌲 Binary Search Trees

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 74  | ⭐ **Validate Binary Search Tree** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DFS, Recursion, Range | Checking BST validity requires passing down min/max constraints. | [LC](https://leetcode.com/problems/validate-binary-search-tree/), Blind 75
| 75  | ⭐ **Kth Smallest Element in a BST** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Inorder Traversal, DFS | Leverages the inorder traversal property of BSTs. | [LC](https://leetcode.com/problems/kth-smallest-element-in-a-bst/), Blind 75
| 76  | ⭐ **Lowest Common Ancestor of a BST** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BST Properties, DFS | Utilizes BST properties for efficient LCA finding. | [LC](https://leetcode.com/problems/lowest-common-ancestor-of-a-bst/), Blind 75

---

## 🌲 Advanced Tree Problems

> **Focus:** Advanced Trees · Complex recursive patterns · Tree construction & serialization

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 77  | **Construct Binary Tree from Preorder and Inorder Traversal** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Recursion, Hashing | Classic tree construction problem using traversal properties. | [LC](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/), Blind 75
| 78  | ⭐ **Binary Tree Maximum Path Sum** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DFS, Recursion | Tricky recursion where path can start/end anywhere. Requires careful state return. | [LC](https://leetcode.com/problems/binary-tree-maximum-path-sum/), Blind 75
| 79  | **Serialize and Deserialize Binary Tree** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DFS/BFS, String | Design problem involving tree representation as a string. | [LC](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/), Blind 75

---

## 🔎 Trie (Prefix Tree)

> **Focus:** Trie Data Structure · Prefix-based Searching · Dictionary Problems · Autocomplete & Word Games

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 80  | ⭐ **Implement Trie (Prefix Tree)** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, Design | Foundational data structure for string/dictionary problems. | [LC](https://leetcode.com/problems/implement-trie-prefix-tree/), Blind 75
| 81  | **Design Add and Search Words Data Structure** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, DFS, Backtracking | Extends Trie with wildcard search. Tests recursive search logic. | [LC](https://leetcode.com/problems/design-add-and-search-words-data-structure/), Blind 75
| 82  | **Word Search II** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Trie, Backtracking, DFS | Combines Trie efficiency with grid backtracking. Highly practical. | [LC](https://leetcode.com/problems/word-search-ii/), Blind 75
| 83  | **Prefix and Suffix Search** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Trie, Design | Designing a structure for efficient prefix/suffix queries on words. | [NeetCode](https://leetcode.com/problems/prefix-and-suffix-search/)
| 84  | **Replace Words** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Trie, String | Using Trie to find shortest matching prefix efficiently. | [LC](https://leetcode.com/problems/replace-words/), NeetCode
| 85  | **Stream of Characters** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Trie, Stream Processing | Matching words in a stream using Trie with suffix tracking. | [NeetCode](https://leetcode.com/problems/stream-of-characters/)

---

## 🔺 Heaps & Priority Queue

> **Focus:** Min/Max Heap · Heap Sort · Classic Heap Problems

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 86  | **Kth Largest Element in an Array** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Heap, QuickSelect | Finding the specific Kth element efficiently. | [LC](https://leetcode.com/problems/kth-largest-element-in-an-array/), NeetCode
| 87  | **Task Scheduler** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Heap, Hashing | Scheduling tasks with cooldowns — solved greedily or with a max-heap. | [LC](https://leetcode.com/problems/task-scheduler/), NeetCode
| 88  | **Find Median from Data Stream** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Two Heaps (Max/Min) | Classic design problem using two heaps to maintain median in streaming fashion. | [LC](https://leetcode.com/problems/find-median-from-data-stream/), Blind 75

---

## 💡 Greedy

> **Focus:** Greedy Paradigm · Making Locally Optimal Choices · Classic Greedy Problems · Practical Applications

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 89  | **Jump Game** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy | Checking reachability by tracking the maximum reachable index greedily. | [LC](https://leetcode.com/problems/jump-game/), Blind 75
| 90  | **Jump Game II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, BFS | Finding the minimum jumps. Solved greedily or as BFS level order. | [LC](https://leetcode.com/problems/jump-game-ii/), NeetCode
| 91  | **Gas Station** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy | Classic greedy problem — proving existence and finding a valid starting point. | [LC](https://leetcode.com/problems/gas-station/), NeetCode
| 92  | **Partition Labels** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Two Pointers | Finding the smallest partitions such that each letter appears in at most one part. | [LC](https://leetcode.com/problems/partition-labels/), NeetCode
| 93  | **Hand of Straights** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Hashing | Forming consecutive groups greedily using counts. | [NeetCode](https://leetcode.com/problems/hand-of-straights/)
| 94  | **Interval Scheduling Maximization** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Sorting | Maximizing event attendance using greedy interval selection. | [LC](https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/), NeetCode

---

## 💻 Dynamic Programming

> **Focus:** Nth Fibonacci Number · Memoization · Tabulation · Classic DP Problems

### 💻 1D Dynamic Programming

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 95  | ⭐ **Climbing Stairs** | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | DP (Fibonacci) | The introductory DP problem, equivalent to Fibonacci sequence. | [LC](https://leetcode.com/problems/climbing-stairs/), Blind 75
| 96  | ⭐ **Coin Change** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Unbounded Knapsack) | Classic DP for minimum coins. Tests state definition and transitions. | [LC](https://leetcode.com/problems/coin-change/), Blind 75
| 97  | ⭐ **Longest Increasing Subsequence** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, Binary Search | Fundamental subsequence problem. Can be optimized with Binary Search. | [LC](https://leetcode.com/problems/longest-increasing-subsequence/), Blind 75
| 98  | ⭐ **Word Break** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, String | Checking if a string can be segmented using a dictionary. Common string DP. | [LC](https://leetcode.com/problems/word-break/), Blind 75
| 99  | ⭐ **House Robber** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP | Simple 1D DP with non-adjacent constraint. | [LC](https://leetcode.com/problems/house-robber/), Blind 75
| 100 | **House Robber II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP | Circular variation of House Robber. Tests reducing to subproblems. | [LC](https://leetcode.com/problems/house-robber-ii/), Blind 75
| 101 | **Decode Ways** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP, String | Counting ways to decode a numeric string. Tests handling DP states carefully. | [LC](https://leetcode.com/problems/decode-ways/), Blind 75
| 102 | **Partition Equal Subset Sum** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (0/1 Knapsack) | Subset sum variation. Tests boolean DP state. | [LC](https://leetcode.com/problems/partition-equal-subset-sum/), NeetCode

### 🧱 2D & Advanced Dynamic Programming

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 94  | **Unique Paths** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Grid) | Basic 2D DP on a grid. Calculating paths from top-left to bottom-right. | [LC](https://leetcode.com/problems/unique-paths/), Blind 75
| 95  | **Longest Common Subsequence** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (2D String) | Fundamental DP for comparing two sequences. | [LC](https://leetcode.com/problems/longest-common-subsequence/), Blind 75
| 96  | **Edit Distance** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (2D String) | Classic DP for string transformation distance (Levenshtein). | [LC](https://leetcode.com/problems/edit-distance/), NeetCode
| 97  | **Maximal Square** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (Grid) | Finding the largest square of 1s in a binary matrix. | [LC](https://leetcode.com/problems/maximal-square/)
| 98  | **Best Time to Buy and Sell Stock with Cooldown** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | DP (State Machine) | Stock problem requiring state machine DP (buy, sell, cooldown). | [LC](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/), NeetCode
| 99  | **Burst Balloons** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DP (Interval) | Challenging interval DP. Requires thinking about the last operation. | [LC](https://leetcode.com/problems/burst-balloons/), NeetCode
| 100 | **Regular Expression Matching** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | DP, Recursion | Complex DP with `'.'` and `'*'`. Tests careful state transitions. | [LC](https://leetcode.com/problems/regular-expression-matching/)

---

## 🧱 Advanced DP

> **Focus:** Advanced DP Problems

### 🧩 Intervals (Advanced DP adjacent)

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 101 | ⭐ **Insert Interval** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Interval Merging | Inserting a new interval into sorted, non-overlapping intervals and merging. | [LC](https://leetcode.com/problems/insert-interval/), Blind 75
| 102 | ⭐ **Merge Intervals** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Sorting, Intervals | The canonical interval merging problem after sorting by start time. | [LC](https://leetcode.com/problems/merge-intervals/), Blind 75
| 103 | ⭐ **Non-overlapping Intervals** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Greedy, Sorting | Finding minimum removals to make intervals non-overlapping. | [LC](https://leetcode.com/problems/non-overlapping-intervals/), Blind 75
| 104 | **Meeting Rooms** *(Premium)* | ![Easy](https://img.shields.io/badge/-Easy-green?style=flat-square) | Sorting, Intervals | Checking if a person can attend all meetings (no overlaps). | Blind 75, [NeetCode](https://leetcode.com/problems/meeting-rooms/)
| 105 | ⭐ **Meeting Rooms II** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Heap, Sorting | Finding the minimum number of rooms required. | Blind 75, [NeetCode](https://leetcode.com/problems/meeting-rooms-ii/)
| 106 | **Minimum Interval to Include Each Query** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Heap, Sorting, Sweep Line | Advanced interval querying using heaps and sorting. | [NeetCode](https://leetcode.com/problems/minimum-interval-to-include-each-query/)

---

## 🌐 Graph Algorithms

> **Focus:** Graph Traversals (BFS & DFS) · Dijkstra's Algorithm · Topological Sorting · Bipartite Graphs · Kruskal's Algorithm · Union-Find

### Graph BFS / DFS

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 107 | ⭐ **Number of Islands** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Grid | The fundamental graph traversal problem on a grid. Counts connected components. | [LC](https://leetcode.com/problems/number-of-islands/), Blind 75
| 108 | ⭐ **Clone Graph** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Hashing | Deep copying graph structure. Tests handling visited nodes. | [LC](https://leetcode.com/problems/clone-graph/), Blind 75
| 109 | **Pacific Atlantic Water Flow** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | BFS/DFS, Grid | Multi-source traversal from oceans inward. Tests simultaneous graph traversals. | [LC](https://leetcode.com/problems/pacific-atlantic-water-flow/), Blind 75

### Dijkstra's Algorithm (Shortest Path)

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 110 | **Network Delay Time** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Dijkstra's/Bellman-Ford | Shortest path from a source in a weighted directed graph. | [LC](https://leetcode.com/problems/network-delay-time/), NeetCode
| 111 | **Cheapest Flights Within K Stops** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Bellman-Ford / Modified Dijkstra | Shortest path with constraint on number of edges. | [NeetCode](https://leetcode.com/problems/cheapest-flights-within-k-stops/)
| 112 | ⭐ **Word Ladder** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | BFS, Implicit Graph | Shortest path on an implicit graph where edges are word transformations. | [LC](https://leetcode.com/problems/word-ladder/), Blind 75

### Topological Sorting & Bipartite Graphs

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 113 | ⭐ **Course Schedule** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Topological Sort (DFS/BFS) | Detecting cycles in a directed graph (prerequisite check). Essential pattern. | [LC](https://leetcode.com/problems/course-schedule/), Blind 75
| 114 | **Course Schedule II** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Topological Sort | Finding a valid course order. Extends Course Schedule I. | [LC](https://leetcode.com/problems/course-schedule-ii/), NeetCode
| 115 | **Alien Dictionary** *(Premium)* | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Topological Sort, Graph Building | Deriving character order from a sorted word list. Complex graph construction. | Blind 75, [NeetCode](https://leetcode.com/problems/alien-dictionary/)

### Union-Find (Kruskal's / Connectivity)

| #   | Problem | Difficulty | Concepts | Description | Source(s)
| :-- | :------ | :--------- | :------- | :------------------ | :----------- |
| 116 | **Redundant Connection** | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find | Finding the edge that creates a cycle. Classic Union-Find application. | [NeetCode](https://leetcode.com/problems/redundant-connection/)
| 117 | **Number of Connected Components** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find, BFS/DFS | Basic connectivity check using Union-Find. | Blind 75, [NeetCode](https://leetcode.com/problems/number-of-connected-components-in-an-undirected-graph/)
| 118 | **Graph Valid Tree** *(Premium)* | ![Medium](https://img.shields.io/badge/-Medium-yellow?style=flat-square) | Union-Find, BFS/DFS | Checking if a graph is a tree (connected and acyclic). | Blind 75, [NeetCode](https://leetcode.com/problems/graph-valid-tree/)
| 119 | **Critical Connections in a Network** | ![Hard](https://img.shields.io/badge/-Hard-red?style=flat-square) | Tarjan's Algorithm (Bridges) | Finding bridges in a graph. Tests understanding of advanced graph algorithms. | [NeetCode](https://leetcode.com/problems/critical-connections-in-a-network/)

---


---

*\*Source Hint: Indicates sources where this problem is frequently listed (LC = LeetCode Top Interview Questions, Blind 75, NeetCode 150). This is indicative, not exhaustive.*

---

## 🚀 Final Thoughts & Next Steps

1. **Understand the Core Concept** — Don't just memorize solutions. Understand *why* a particular approach works.
2. **Practice Variations** — Once you solve a problem, think about variations and follow-up questions.
3. **Time Yourself** — Simulate interview conditions. Can you solve medium problems within 20–30 minutes?
4. **Explain Your Thought Process** — Practice articulating your solution clearly, step-by-step.
5. **Review Regularly** — Spaced repetition helps solidify concepts.

Good luck with your preparation! You've got this! 🌟

---
