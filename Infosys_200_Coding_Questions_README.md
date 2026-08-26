# Infosys 200 Coding Questions — SP / DSE Preparation

> A coding-first preparation sheet for Infosys Specialist Programmer / Digital Specialist Engineer style assessments.

## Why this repository exists
This repository contains **200 coding problems**, split into four sets of 50. It is designed around the recurring patterns seen in Infosys HackWithInfy/SP-DSE preparation material and recent candidate reports: arrays/strings, greedy and sliding window, binary search, trees/graphs, and dynamic programming.

Infosys' own HackWithInfy material explicitly highlights hard topics such as Knapsack, Fibonacci, Palindromic Subsequence, Longest Common Substring and Dijkstra. The official 2025 sample paper also includes an array/subarray optimization problem. citeturn0search43turn0search42

Recent 2026 candidate reports describe coding assessments with Easy/Medium/Hard progression and later rounds involving prefix/precomputation, advanced arrays, trees and graphs. Exact question count and pattern can vary by drive, so use the assessment instructions for your specific campus/drive as the final authority. citeturn0search9turn0search7

## Important PYQ note
Questions marked **PYQ/Official-style** are based on official Infosys sample/past-question themes or reported Infosys problems. The original copyrighted problem statements are not reproduced here; use the official Infosys sample papers for the original wording.

## Recommended exam strategy
- First target complete correctness on the easiest problem.
- Then solve the medium problem with an optimized approach.
- For hard/complex problems, identify the pattern before coding.
- Always check constraints before choosing an algorithm.
- Aim for `O(N)`, `O(N log N)` or another complexity justified by the constraints.
- Test duplicates, empty/small input, maximum values, negative values and overflow.

## 4-section plan

| Section | Questions | Priority |
|---|---:|---|
| 01 — Arrays & Strings | 50 | 🔥🔥🔥🔥🔥 |
| 02 — Greedy, Sliding Window & Binary Search | 50 | 🔥🔥🔥🔥🔥 |
| 03 — Trees, Graphs & Advanced DS | 50 | 🔥🔥🔥🔥 |
| 04 — DP, Recursion, Backtracking & Bit | 50 | 🔥🔥🔥🔥🔥 |

## 01 — Arrays & Strings

- [ ] **01.01** — Array Type Queries — `Prefix sums / query processing` — *PYQ/Official-style*
- [ ] **01.02** — Maximum Sum Subarray with At Most K Distinct Values — `Sliding window / Kadane variant` — *PYQ/Official-style*
- [ ] **01.03** — RPG Monster Defeat — `Sorting / greedy` — *PYQ*
- [ ] **01.04** — Two Sum — `Hash map` — *Practice*
- [ ] **01.05** — Three Sum — `Sorting / two pointers` — *Practice*
- [ ] **01.06** — Maximum Subarray Sum — `Kadane` — *Practice*
- [ ] **01.07** — Maximum Product Subarray — `DP / prefix-suffix` — *Practice*
- [ ] **01.08** — Move Zeroes — `Two pointers` — *Practice*
- [ ] **01.09** — Remove Duplicates from Sorted Array — `Two pointers` — *Practice*
- [ ] **01.10** — Rotate Array by K — `Array manipulation` — *Practice*
- [ ] **01.11** — Merge Two Sorted Arrays — `Two pointers` — *Practice*
- [ ] **01.12** — Merge Intervals — `Sorting` — *Practice*
- [ ] **01.13** — Missing Number — `XOR / math` — *Practice*
- [ ] **01.14** — Find Duplicate Number — `Cycle detection` — *Practice*
- [ ] **01.15** — Majority Element — `Boyer-Moore` — *Practice*
- [ ] **01.16** — Majority Element II — `Counting` — *Practice*
- [ ] **01.17** — Best Time to Buy and Sell Stock — `Greedy` — *Practice*
- [ ] **01.18** — Best Time to Buy and Sell Stock II — `Greedy` — *Practice*
- [ ] **01.19** — Container With Most Water — `Two pointers` — *Practice*
- [ ] **01.20** — Trapping Rain Water — `Two pointers / prefix` — *Practice*
- [ ] **01.21** — Product of Array Except Self — `Prefix/suffix` — *Practice*
- [ ] **01.22** — Subarray Sum Equals K — `Prefix sum + hash map` — *Practice*
- [ ] **01.23** — Longest Consecutive Sequence — `Hash set` — *Practice*
- [ ] **01.24** — Find Pair with Given Difference — `Hashing` — *Practice*
- [ ] **01.25** — Count Inversions — `Merge sort` — *Practice*
- [ ] **01.26** — Kth Largest Element — `Heap / quickselect` — *Practice*
- [ ] **01.27** — Top K Frequent Elements — `Hashing / heap` — *Practice*
- [ ] **01.28** — Sort 0s, 1s and 2s — `Dutch national flag` — *Practice*
- [ ] **01.29** — Next Permutation — `Array manipulation` — *Practice*
- [ ] **01.30** — Spiral Matrix — `Simulation` — *Practice*
- [ ] **01.31** — Set Matrix Zeroes — `In-place marking` — *Practice*
- [ ] **01.32** — Rotate Matrix 90 Degrees — `Matrix` — *Practice*
- [ ] **01.33** — Search in 2D Matrix — `Binary search` — *Practice*
- [ ] **01.34** — Longest Subarray with Sum K — `Prefix sum` — *Practice*
- [ ] **01.35** — Maximum Consecutive Ones III — `Sliding window` — *Practice*
- [ ] **01.36** — Longest Substring Without Repeating Characters — `Sliding window` — *Practice*
- [ ] **01.37** — Longest Palindromic Substring — `Expand around center` — *Practice*
- [ ] **01.38** — Valid Anagram — `Frequency map` — *Practice*
- [ ] **01.39** — Group Anagrams — `Hashing` — *Practice*
- [ ] **01.40** — Valid Parentheses — `Stack` — *Practice*
- [ ] **01.41** — Minimum Remove to Make Valid Parentheses — `Stack` — *Practice*
- [ ] **01.42** — Longest Valid Parentheses — `Stack / DP` — *Practice*
- [ ] **01.43** — String Compression — `Two pointers` — *Practice*
- [ ] **01.44** — Run-Length Encoding — `String simulation` — *Practice*
- [ ] **01.45** — Minimum Window Substring — `Sliding window` — *Practice*
- [ ] **01.46** — Find All Anagrams in a String — `Sliding window` — *Practice*
- [ ] **01.47** — Longest Common Prefix — `String` — *Practice*
- [ ] **01.48** — Implement strstr — `String matching` — *Practice*
- [ ] **01.49** — String to Integer (atoi) — `Parsing` — *Practice*
- [ ] **01.50** — Count Distinct Elements in Every Window — `Sliding window + hash map` — *Practice*

## 02 — Greedy, Sliding Window & Binary Search

- [ ] **02.01** — Minimum Ugliness of Binary String — `Greedy / sliding window` — *PYQ-style*
- [ ] **02.02** — Packing Gifts into K Boxes — `Greedy / sorting` — *PYQ-style*
- [ ] **02.03** — Counting Divisible Arrays — `Number theory / optimization` — *PYQ-style*
- [ ] **02.04** — Activity Selection — `Greedy` — *Practice*
- [ ] **02.05** — Fractional Knapsack — `Greedy` — *Practice*
- [ ] **02.06** — Job Sequencing with Deadlines — `Greedy` — *Practice*
- [ ] **02.07** — Minimum Number of Platforms — `Sorting / two pointers` — *Practice*
- [ ] **02.08** — Assign Cookies — `Greedy` — *Practice*
- [ ] **02.09** — Lemonade Change — `Greedy` — *Practice*
- [ ] **02.10** — Jump Game — `Greedy` — *Practice*
- [ ] **02.11** — Jump Game II — `Greedy` — *Practice*
- [ ] **02.12** — Gas Station — `Greedy` — *Practice*
- [ ] **02.13** — Candy Distribution — `Greedy` — *Practice*
- [ ] **02.14** — Non-overlapping Intervals — `Greedy` — *Practice*
- [ ] **02.15** — Meeting Rooms II — `Heap / greedy` — *Practice*
- [ ] **02.16** — Minimum Arrows to Burst Balloons — `Greedy` — *Practice*
- [ ] **02.17** — Partition Labels — `Greedy` — *Practice*
- [ ] **02.18** — Hand of Straights — `Greedy + map` — *Practice*
- [ ] **02.19** — Boats to Save People — `Two pointers` — *Practice*
- [ ] **02.20** — Minimum Coins for Value — `Greedy` — *Practice*
- [ ] **02.21** — Maximum Units on a Truck — `Greedy` — *Practice*
- [ ] **02.22** — Queue Reconstruction by Height — `Greedy` — *Practice*
- [ ] **02.23** — Merge Triplets to Form Target — `Greedy` — *Practice*
- [ ] **02.24** — Remove K Digits — `Monotonic stack / greedy` — *Practice*
- [ ] **02.25** — Task Scheduler — `Greedy / counting` — *Practice*
- [ ] **02.26** — Sliding Window Maximum — `Deque` — *Practice*
- [ ] **02.27** — First Negative in Every Window — `Deque` — *Practice*
- [ ] **02.28** — Maximum Sum of Fixed Window — `Sliding window` — *Practice*
- [ ] **02.29** — Minimum Size Subarray Sum — `Sliding window` — *Practice*
- [ ] **02.30** — Longest Repeating Character Replacement — `Sliding window` — *Practice*
- [ ] **02.31** — Permutation in String — `Sliding window` — *Practice*
- [ ] **02.32** — Fruit Into Baskets — `Sliding window` — *Practice*
- [ ] **02.33** — Max Consecutive Ones III — `Sliding window` — *Practice*
- [ ] **02.34** — Binary Subarrays With Sum — `Sliding window / prefix` — *Practice*
- [ ] **02.35** — Count Number of Nice Subarrays — `Prefix / sliding window` — *Practice*
- [ ] **02.36** — Subarrays with K Different Integers — `Sliding window` — *Practice*
- [ ] **02.37** — Find Peak Element — `Binary search` — *Practice*
- [ ] **02.38** — Search in Rotated Sorted Array — `Binary search` — *Practice*
- [ ] **02.39** — Search in Rotated Sorted Array II — `Binary search` — *Practice*
- [ ] **02.40** — Find Minimum in Rotated Sorted Array — `Binary search` — *Practice*
- [ ] **02.41** — First and Last Position of Element — `Binary search` — *Practice*
- [ ] **02.42** — Koko Eating Bananas — `Binary search on answer` — *Practice*
- [ ] **02.43** — Capacity to Ship Packages — `Binary search on answer` — *Practice*
- [ ] **02.44** — Aggressive Cows — `Binary search on answer` — *Practice*
- [ ] **02.45** — Allocate Minimum Pages — `Binary search on answer` — *Practice*
- [ ] **02.46** — Split Array Largest Sum — `Binary search on answer` — *Practice*
- [ ] **02.47** — Median of Two Sorted Arrays — `Binary search` — *Practice*
- [ ] **02.48** — Nth Root of a Number — `Binary search` — *Practice*
- [ ] **02.49** — Minimum Days to Make Bouquets — `Binary search on answer` — *Practice*
- [ ] **02.50** — Painter's Partition — `Binary search on answer` — *Practice*

## 03 — Trees, Graphs & Advanced Data Structures

- [ ] **03.01** — Longest Increasing Path in Matrix — `DFS + memoization` — *PYQ-style*
- [ ] **03.02** — Graph Queries with DSU — `Graph / disjoint set union` — *PYQ-style*
- [ ] **03.03** — Advanced Tree Query — `Tree algorithms` — *PYQ-style*
- [ ] **03.04** — Binary Tree Preorder Traversal — `Tree traversal` — *Practice*
- [ ] **03.05** — Binary Tree Inorder Traversal — `Tree traversal` — *Practice*
- [ ] **03.06** — Binary Tree Postorder Traversal — `Tree traversal` — *Practice*
- [ ] **03.07** — Level Order Traversal — `BFS` — *Practice*
- [ ] **03.08** — Zigzag Level Order Traversal — `BFS` — *Practice*
- [ ] **03.09** — Maximum Depth of Binary Tree — `DFS` — *Practice*
- [ ] **03.10** — Diameter of Binary Tree — `Tree DP` — *Practice*
- [ ] **03.11** — Balanced Binary Tree — `DFS` — *Practice*
- [ ] **03.12** — Same Tree — `DFS` — *Practice*
- [ ] **03.13** — Symmetric Tree — `DFS / BFS` — *Practice*
- [ ] **03.14** — Invert Binary Tree — `Tree recursion` — *Practice*
- [ ] **03.15** — Path Sum — `DFS` — *Practice*
- [ ] **03.16** — Path Sum II — `Backtracking` — *Practice*
- [ ] **03.17** — Maximum Path Sum in Binary Tree — `Tree DP` — *Practice*
- [ ] **03.18** — Lowest Common Ancestor — `Tree` — *Practice*
- [ ] **03.19** — Validate Binary Search Tree — `BST` — *Practice*
- [ ] **03.20** — Kth Smallest in BST — `Inorder / heap` — *Practice*
- [ ] **03.21** — Construct Tree from Traversals — `Tree recursion` — *Practice*
- [ ] **03.22** — Serialize and Deserialize Binary Tree — `Tree / BFS` — *Practice*
- [ ] **03.23** — Right Side View of Binary Tree — `BFS` — *Practice*
- [ ] **03.24** — Boundary Traversal — `Tree traversal` — *Practice*
- [ ] **03.25** — Vertical Order Traversal — `Tree + sorting` — *Practice*
- [ ] **03.26** — Top View of Binary Tree — `BFS` — *Practice*
- [ ] **03.27** — Bottom View of Binary Tree — `BFS` — *Practice*
- [ ] **03.28** — Count Complete Tree Nodes — `Binary search / tree` — *Practice*
- [ ] **03.29** — Trie Insert Search Prefix — `Trie` — *Practice*
- [ ] **03.30** — Word Search — `Backtracking` — *Practice*
- [ ] **03.31** — Number of Islands — `BFS / DFS` — *Practice*
- [ ] **03.32** — Flood Fill — `BFS / DFS` — *Practice*
- [ ] **03.33** — Rotting Oranges — `Multi-source BFS` — *Practice*
- [ ] **03.34** — Clone Graph — `BFS / DFS` — *Practice*
- [ ] **03.35** — Course Schedule — `Topological sort` — *Practice*
- [ ] **03.36** — Course Schedule II — `Topological sort` — *Practice*
- [ ] **03.37** — Detect Cycle in Undirected Graph — `DFS / DSU` — *Practice*
- [ ] **03.38** — Detect Cycle in Directed Graph — `DFS` — *Practice*
- [ ] **03.39** — Bipartite Graph — `BFS / DFS` — *Practice*
- [ ] **03.40** — Shortest Path in Unweighted Graph — `BFS` — *Practice*
- [ ] **03.41** — Dijkstra Shortest Path — `Priority queue` — *Practice*
- [ ] **03.42** — Bellman-Ford — `Shortest path` — *Practice*
- [ ] **03.43** — Floyd-Warshall — `All-pairs shortest path` — *Practice*
- [ ] **03.44** — Minimum Spanning Tree - Kruskal — `DSU` — *Practice*
- [ ] **03.45** — Minimum Spanning Tree - Prim — `Heap` — *Practice*
- [ ] **03.46** — Number of Provinces — `DSU / DFS` — *Practice*
- [ ] **03.47** — Network Delay Time — `Dijkstra` — *Practice*
- [ ] **03.48** — Word Ladder — `BFS` — *Practice*
- [ ] **03.49** — Articulation Points — `DFS` — *Practice*
- [ ] **03.50** — Bridges in Graph — `Tarjan DFS` — *Practice*

## 04 — Dynamic Programming, Recursion, Backtracking & Bit Manipulation

- [ ] **04.01** — Knapsack — `Dynamic programming` — *PYQ/Official-style*
- [ ] **04.02** — Fibonacci / memoization — `Dynamic programming` — *PYQ/Official-style*
- [ ] **04.03** — Palindromic Subsequence — `2D DP` — *PYQ/Official-style*
- [ ] **04.04** — Longest Common Substring — `2D DP` — *PYQ/Official-style*
- [ ] **04.05** — Dijkstra's Algorithm — `Shortest path` — *PYQ/Official-style*
- [ ] **04.06** — Longest Common Subsequence — `2D DP` — *PYQ-style*
- [ ] **04.07** — Max XOR-Sum in Range — `Bit manipulation / greedy` — *PYQ-style*
- [ ] **04.08** — Max XOR of Half-Sized Subset — `Bit manipulation` — *PYQ-style*
- [ ] **04.09** — Climbing Stairs — `1D DP` — *Practice*
- [ ] **04.10** — House Robber — `1D DP` — *Practice*
- [ ] **04.11** — House Robber II — `DP on circle` — *Practice*
- [ ] **04.12** — Coin Change — `Unbounded knapsack` — *Practice*
- [ ] **04.13** — Coin Change II — `Counting DP` — *Practice*
- [ ] **04.14** — Subset Sum — `0/1 knapsack` — *Practice*
- [ ] **04.15** — Partition Equal Subset Sum — `0/1 DP` — *Practice*
- [ ] **04.16** — Minimum Subset Sum Difference — `Knapsack DP` — *Practice*
- [ ] **04.17** — Count Subsets with Given Sum — `Counting DP` — *Practice*
- [ ] **04.18** — Target Sum — `Subset DP` — *Practice*
- [ ] **04.19** — 0/1 Knapsack — `Knapsack DP` — *Practice*
- [ ] **04.20** — Unbounded Knapsack — `Knapsack DP` — *Practice*
- [ ] **04.21** — Rod Cutting — `Unbounded DP` — *Practice*
- [ ] **04.22** — Longest Increasing Subsequence — `LIS` — *Practice*
- [ ] **04.23** — Longest Decreasing Subsequence — `LDS` — *Practice*
- [ ] **04.24** — Maximum Sum Increasing Subsequence — `LIS DP` — *Practice*
- [ ] **04.25** — Number of LIS — `LIS DP` — *Practice*
- [ ] **04.26** — Russian Doll Envelopes — `LIS + sorting` — *Practice*
- [ ] **04.27** — Longest Bitonic Subsequence — `LIS/LDS` — *Practice*
- [ ] **04.28** — Edit Distance — `2D DP` — *Practice*
- [ ] **04.29** — Distinct Subsequences — `2D DP` — *Practice*
- [ ] **04.30** — Interleaving String — `2D DP` — *Practice*
- [ ] **04.31** — Word Break — `String DP` — *Practice*
- [ ] **04.32** — Palindrome Partitioning II — `Interval DP` — *Practice*
- [ ] **04.33** — Longest Palindromic Subsequence — `2D DP` — *Practice*
- [ ] **04.34** — Minimum Insertions for Palindrome — `2D DP` — *Practice*
- [ ] **04.35** — Matrix Chain Multiplication — `Interval DP` — *Practice*
- [ ] **04.36** — Burst Balloons — `Interval DP` — *Practice*
- [ ] **04.37** — Unique Paths — `Grid DP` — *Practice*
- [ ] **04.38** — Unique Paths II — `Grid DP` — *Practice*
- [ ] **04.39** — Minimum Path Sum — `Grid DP` — *Practice*
- [ ] **04.40** — Triangle Minimum Path — `Grid DP` — *Practice*
- [ ] **04.41** — Maximum Falling Path Sum — `Grid DP` — *Practice*
- [ ] **04.42** — Cherry Pickup — `Grid DP` — *Practice*
- [ ] **04.43** — N-Queens — `Backtracking` — *Practice*
- [ ] **04.44** — Sudoku Solver — `Backtracking` — *Practice*
- [ ] **04.45** — Generate Parentheses — `Backtracking` — *Practice*
- [ ] **04.46** — Combination Sum — `Backtracking` — *Practice*
- [ ] **04.47** — Permutations — `Backtracking` — *Practice*
- [ ] **04.48** — Subsets — `Backtracking` — *Practice*
- [ ] **04.49** — Single Number — `XOR` — *Practice*
- [ ] **04.50** — Counting Set Bits — `Bit manipulation` — *Practice*

## How to use this repository

### Phase 1 — Foundation
Solve 01.01–01.50. Do not look at solutions until you have written your own approach.

### Phase 2 — Optimization
Solve 02.01–02.50. For every solution, write down the time and space complexity.

### Phase 3 — Trees and graphs
Solve 03.01–03.50. Be comfortable with BFS, DFS, DSU, Dijkstra and topological sort.

### Phase 4 — Hard problems
Solve 04.01–04.50. Prioritize knapsack, LIS, LCS, grid DP, interval DP and backtracking.

### Phase 5 — Mock tests
Create 3-hour mocks using 1 easy + 1 medium + 1 hard problem. Later use 4-question mocks for drives/rounds that use four questions.

## Suggested folder structure

```text
infosys-200-coding/
├── README.md
├── 01-arrays-strings/
├── 02-greedy-sliding-window-binary-search/
├── 03-trees-graphs-advanced-ds/
├── 04-dp-recursion-backtracking-bit/
└── notes/
    ├── complexity.md
    ├── templates.md
    └── mistakes.md
```

## C++ template

```cpp
#include <bits/stdc++.h>
using namespace std;

int main() {
    ios::sync_with_stdio(false);
    cin.tie(nullptr);

    // solve here
    return 0;
}
```

## What to master before the exam
- [ ] Prefix sum and difference array
- [ ] Hash map / hash set
- [ ] Two pointers
- [ ] Sliding window
- [ ] Binary search and binary search on answer
- [ ] Stack / monotonic stack
- [ ] Heap / priority queue
- [ ] BFS / DFS
- [ ] DSU
- [ ] Dijkstra
- [ ] Topological sort
- [ ] 0/1 and unbounded knapsack
- [ ] LIS / LCS
- [ ] Grid DP
- [ ] Interval DP
- [ ] Memoization vs tabulation
- [ ] Recursion and backtracking
- [ ] XOR and bit manipulation

## Official / reference resources
- Infosys HackWithInfy official sample questions: https://www.infosys.com/careers/hackwithinfy/2025/sample-questions_hwi.pdf
- Infosys preparatory guidance: https://www.infosys.com/careers/hackwithinfy/2024/images/preparatory-guidance-hwi.pdf

## Disclaimer
This is a preparation repository, not an official Infosys question bank. Patterns and assessment formats can change between drives. PYQ labels identify reported/official-source themes; practice problems are intentionally included to cover the algorithms needed to solve variants.

### Goal
**200 problems → learn the pattern → code from scratch → optimize → test edge cases → repeat.**