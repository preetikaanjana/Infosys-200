# Infosys 200 Coding Questions — SP / DSE Preparation

> A coding-first preparation sheet for Infosys Specialist Programmer / Digital Specialist Engineer style assessments.

## Why this repository exists
This repository contains **200 coding problems**, split into four sets of 50. It is designed around the recurring patterns seen in Infosys HackWithInfy/SP-DSE preparation material and recent candidate reports: arrays/strings, greedy and sliding window, binary search, trees/graphs, and dynamic programming.

Infosys' own HackWithInfy material explicitly highlights hard topics such as Knapsack, Fibonacci, Palindromic Subsequence, Longest Common Substring and Dijkstra. The official 2025 sample paper also includes an array/subarray optimization problem. citeturn0search43turn0search42

Recent 2026 candidate reports describe coding assessments with Easy/Medium/Hard progression and later rounds involving prefix/precomputation, advanced arrays, trees and graphs. Exact question count and pattern can vary by drive, so use the assessment instructions for your specific campus/drive as the final authority. citeturn0search9turn0search7

## Practice links
Each problem now has a practice link. Direct LeetCode links are used where an exact matching problem exists; GFG search links are used for classic problems whose exact GFG URL varies; a few advanced graph problems use direct Codeforces links. For PYQ/official-style items that are custom/official themes rather than exact public copies, the link is to a related practice problem so you can train the same pattern.

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

- [ ] **01.01** — Array Type Queries — `Prefix sums / query processing` — *PYQ/Official-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Array+Type+Queries)
- [ ] **01.02** — Maximum Sum Subarray with At Most K Distinct Values — `Sliding window / Kadane variant` — *PYQ/Official-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Maximum+Sum+Subarray+with+At+Most+K+Distinct+Values)
- [ ] **01.03** — RPG Monster Defeat — `Sorting / greedy` — *PYQ* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=RPG+Monster+Defeat)
- [✅] **01.04** — Two Sum — `Hash map` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/two-sum/)
- [✅] **01.05** — Three Sum — `Sorting / two pointers` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/3sum/)
- [✅] **01.06** — Maximum Subarray Sum — `Kadane` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/maximum-subarray/)
- [✅] **01.07** — Maximum Product Subarray — `DP / prefix-suffix` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/maximum-product-subarray/)
- [✅] **01.08** — Move Zeroes — `Two pointers` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/move-zeroes/)
- [✅] **01.09** — Remove Duplicates from Sorted Array — `Two pointers` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/remove-duplicates-from-sorted-array/)
- [ ] **01.10** — Rotate Array by K — `Array manipulation` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/rotate-array/)
- [✅] **01.11** — Merge Two Sorted Arrays — `Two pointers` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/merge-sorted-array/)
- [ ] **01.12** — Merge Intervals — `Sorting` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/merge-intervals/)
- [✅] **01.13** — Missing Number — `XOR / math` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/missing-number/)
- [✅] **01.14** — Find Duplicate Number — `Cycle detection` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/find-the-duplicate-number/)
- [✅] **01.15** — Majority Element — `Boyer-Moore` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/majority-element/)
- [✅] **01.16** — Majority Element II — `Counting` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/majority-element-ii/)
- [✅] **01.17** — Best Time to Buy and Sell Stock — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
- [✅] **01.18** — Best Time to Buy and Sell Stock II — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-ii/)
- [✅] **01.19** — Container With Most Water — `Two pointers` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/container-with-most-water/)
- [✅] **01.20** — Trapping Rain Water — `Two pointers / prefix` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/trapping-rain-water/)
- [✅] **01.21** — Product of Array Except Self — `Prefix/suffix` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/product-of-array-except-self/)
- [✅] **01.22** — Subarray Sum Equals K — `Prefix sum + hash map` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/subarray-sum-equals-k/)
- [✅] **01.23** — Longest Consecutive Sequence — `Hash set` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-consecutive-sequence/)
- [✅] **01.24** — Find Pair with Given Difference — `Hashing` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Find+Pair+with+Given+Difference)
- [ ] **01.25** — Count Inversions — `Merge sort` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Count+Inversions)
- [✅] **01.26** — Kth Largest Element — `Heap / quickselect` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- [✅] **01.27** — Top K Frequent Elements — `Hashing / heap` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/top-k-frequent-elements/)
- [✅] **01.28** — Sort 0s, 1s and 2s — `Dutch national flag` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/sort-colors/)
- [✅] **01.29** — Next Permutation — `Array manipulation` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/next-permutation/)
- [✅] **01.30** — Spiral Matrix — `Simulation` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/spiral-matrix/)
- [✅] **01.31** — Set Matrix Zeroes — `In-place marking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/set-matrix-zeroes/)
- [✅] **01.32** — Rotate Matrix 90 Degrees — `Matrix` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/rotate-image/)
- [✅] **01.33** — Search in 2D Matrix — `Binary search` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/search-a-2d-matrix/)
- [ ] **01.34** — Longest Subarray with Sum K — `Prefix sum` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Longest+Subarray+with+Sum+K)
- [ ] **01.35** — Maximum Consecutive Ones III — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/max-consecutive-ones-iii/)
- [ ] **01.36** — Longest Substring Without Repeating Characters — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [ ] **01.37** — Longest Palindromic Substring — `Expand around center` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-palindromic-substring/)
- [✅] **01.38** — Valid Anagram — `Frequency map` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/valid-anagram/)
- [ ] **01.39** — Group Anagrams — `Hashing` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/group-anagrams/)
- [✅] **01.40** — Valid Parentheses — `Stack` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/valid-parentheses/)
- [ ] **01.41** — Minimum Remove to Make Valid Parentheses — `Stack` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/)
- [ ] **01.42** — Longest Valid Parentheses — `Stack / DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-valid-parentheses/)
- [ ] **01.43** — String Compression — `Two pointers` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/string-compression/)
- [ ] **01.44** — Run-Length Encoding — `String simulation` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Run-Length+Encoding)
- [ ] **01.45** — Minimum Window Substring — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-window-substring/)
- [ ] **01.46** — Find All Anagrams in a String — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/find-all-anagrams-in-a-string/)
- [ ] **01.47** — Longest Common Prefix — `String` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-common-prefix/)
- [ ] **01.48** — Implement strstr — `String matching` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Implement+strstr)
- [ ] **01.49** — String to Integer (atoi) — `Parsing` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/string-to-integer-atoi/)
- [ ] **01.50** — Count Distinct Elements in Every Window — `Sliding window + hash map` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/contains-duplicate-ii/)

## 02 — Greedy, Sliding Window & Binary Search

- [ ] **02.01** — Minimum Ugliness of Binary String — `Greedy / sliding window` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Minimum+Ugliness+of+Binary+String)
- [ ] **02.02** — Packing Gifts into K Boxes — `Greedy / sorting` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Packing+Gifts+into+K+Boxes)
- [ ] **02.03** — Counting Divisible Arrays — `Number theory / optimization` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Counting+Divisible+Arrays)
- [ ] **02.04** — Activity Selection — `Greedy` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Activity+Selection)
- [ ] **02.05** — Fractional Knapsack — `Greedy` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Fractional+Knapsack)
- [ ] **02.06** — Job Sequencing with Deadlines — `Greedy` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Job+Sequencing+with+Deadlines)
- [ ] **02.07** — Minimum Number of Platforms — `Sorting / two pointers` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Minimum+Number+of+Platforms)
- [ ] **02.08** — Assign Cookies — `Greedy` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Assign+Cookies)
- [ ] **02.09** — Lemonade Change — `Greedy` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Lemonade+Change)
- [ ] **02.10** — Jump Game — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/jump-game/)
- [ ] **02.11** — Jump Game II — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/jump-game-ii/)
- [ ] **02.12** — Gas Station — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/gas-station/)
- [ ] **02.13** — Candy Distribution — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/candy/)
- [ ] **02.14** — Non-overlapping Intervals — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/non-overlapping-intervals/)
- [ ] **02.15** — Meeting Rooms II — `Heap / greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/meeting-rooms-ii/)
- [ ] **02.16** — Minimum Arrows to Burst Balloons — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-number-of-arrows-to-burst-balloons/)
- [ ] **02.17** — Partition Labels — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/partition-labels/)
- [ ] **02.18** — Hand of Straights — `Greedy + map` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/hand-of-straights/)
- [ ] **02.19** — Boats to Save People — `Two pointers` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/boats-to-save-people/)
- [ ] **02.20** — Minimum Coins for Value — `Greedy` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Minimum+Coins+for+Value)
- [ ] **02.21** — Maximum Units on a Truck — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/maximum-units-on-a-truck/)
- [ ] **02.22** — Queue Reconstruction by Height — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/queue-reconstruction-by-height/)
- [ ] **02.23** — Merge Triplets to Form Target — `Greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/merge-triplets-to-form-target/)
- [ ] **02.24** — Remove K Digits — `Monotonic stack / greedy` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/remove-k-digits/)
- [ ] **02.25** — Task Scheduler — `Greedy / counting` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/task-scheduler/)
- [ ] **02.26** — Sliding Window Maximum — `Deque` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/sliding-window-maximum/)
- [ ] **02.27** — First Negative in Every Window — `Deque` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=First+Negative+in+Every+Window)
- [ ] **02.28** — Maximum Sum of Fixed Window — `Sliding window` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Maximum+Sum+of+Fixed+Window)
- [ ] **02.29** — Minimum Size Subarray Sum — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-size-subarray-sum/)
- [ ] **02.30** — Longest Repeating Character Replacement — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-repeating-character-replacement/)
- [ ] **02.31** — Permutation in String — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/permutation-in-string/)
- [ ] **02.32** — Fruit Into Baskets — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/fruit-into-baskets/)
- [ ] **02.33** — Max Consecutive Ones III — `Sliding window` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Max+Consecutive+Ones+III)
- [ ] **02.34** — Binary Subarrays With Sum — `Sliding window / prefix` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-subarrays-with-sum/)
- [ ] **02.35** — Count Number of Nice Subarrays — `Prefix / sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/count-number-of-nice-subarrays/)
- [ ] **02.36** — Subarrays with K Different Integers — `Sliding window` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/subarrays-with-k-different-integers/)
- [✅] **02.37** — Find Peak Element — `Binary search` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/find-peak-element/)
- [✅] **02.38** — Search in Rotated Sorted Array — `Binary search` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- [✅] **02.39** — Search in Rotated Sorted Array II — `Binary search` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/)
- [✅] **02.40** — Find Minimum in Rotated Sorted Array — `Binary search` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
- [✅] **02.41** — First and Last Position of Element — `Binary search` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
- [ ] **02.42** — Koko Eating Bananas — `Binary search on answer` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/koko-eating-bananas/)
- [ ] **02.43** — Capacity to Ship Packages — `Binary search on answer` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/)
- [ ] **02.44** — Aggressive Cows — `Binary search on answer` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Aggressive+Cows)
- [ ] **02.45** — Allocate Minimum Pages — `Binary search on answer` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Allocate+Minimum+Pages)
- [ ] **02.46** — Split Array Largest Sum — `Binary search on answer` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/split-array-largest-sum/)
- [ ] **02.47** — Median of Two Sorted Arrays — `Binary search` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/median-of-two-sorted-arrays/)
- [ ] **02.48** — Nth Root of a Number — `Binary search` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Nth+Root+of+a+Number)
- [ ] **02.49** — Minimum Days to Make Bouquets — `Binary search on answer` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/)
- [ ] **02.50** — Painter's Partition — `Binary search on answer` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Painter%27s+Partition)

## 03 — Trees, Graphs & Advanced Data Structures

- [ ] **03.01** — Longest Increasing Path in Matrix — `DFS + memoization` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Longest+Increasing+Path+in+Matrix)
- [ ] **03.02** — Graph Queries with DSU — `Graph / disjoint set union` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Graph+Queries+with+DSU)
- [ ] **03.03** — Advanced Tree Query — `Tree algorithms` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Advanced+Tree+Query)
- [✅] **03.04** — Binary Tree Preorder Traversal — `Tree traversal` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-tree-preorder-traversal/)
- [✅] **03.05** — Binary Tree Inorder Traversal — `Tree traversal` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-tree-inorder-traversal/)
- [✅] **03.06** — Binary Tree Postorder Traversal — `Tree traversal` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-tree-postorder-traversal/)
- [✅] **03.07** — Level Order Traversal — `BFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-tree-level-order-traversal/)
- [✅] **03.08** — Zigzag Level Order Traversal — `BFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)
- [✅] **03.09** — Maximum Depth of Binary Tree — `DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
- [✅] **03.10** — Diameter of Binary Tree — `Tree DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/diameter-of-binary-tree/)
- [✅] **03.11** — Balanced Binary Tree — `DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/balanced-binary-tree/)
- [ ] **03.12** — Same Tree — `DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/same-tree/)
- [ ] **03.13** — Symmetric Tree — `DFS / BFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/symmetric-tree/)
- [ ] **03.14** — Invert Binary Tree — `Tree recursion` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/invert-binary-tree/)
- [ ] **03.15** — Path Sum — `DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/path-sum/)
- [ ] **03.16** — Path Sum II — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/path-sum-ii/)
- [ ] **03.17** — Maximum Path Sum in Binary Tree — `Tree DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-tree-maximum-path-sum/)
- [ ] **03.18** — Lowest Common Ancestor — `Tree` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/)
- [ ] **03.19** — Validate Binary Search Tree — `BST` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/validate-binary-search-tree/)
- [ ] **03.20** — Kth Smallest in BST — `Inorder / heap` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
- [ ] **03.21** — Construct Tree from Traversals — `Tree recursion` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
- [ ] **03.22** — Serialize and Deserialize Binary Tree — `Tree / BFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)
- [ ] **03.23** — Right Side View of Binary Tree — `BFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/binary-tree-right-side-view/)
- [ ] **03.24** — Boundary Traversal — `Tree traversal` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Boundary+Traversal)
- [ ] **03.25** — Vertical Order Traversal — `Tree + sorting` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Vertical+Order+Traversal)
- [ ] **03.26** — Top View of Binary Tree — `BFS` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Top+View+of+Binary+Tree)
- [ ] **03.27** — Bottom View of Binary Tree — `BFS` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Bottom+View+of+Binary+Tree)
- [ ] **03.28** — Count Complete Tree Nodes — `Binary search / tree` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/count-complete-tree-nodes/)
- [ ] **03.29** — Trie Insert Search Prefix — `Trie` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Trie+Insert+Search+Prefix)
- [ ] **03.30** — Word Search — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/word-search/)
- [✅] **03.31** — Number of Islands — `BFS / DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/number-of-islands/)
- [✅] **03.32** — Flood Fill — `BFS / DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/flood-fill/)
- [✅] **03.33** — Rotting Oranges — `Multi-source BFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/rotting-oranges/)
- [ ] **03.34** — Clone Graph — `BFS / DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/clone-graph/)
- [ ] **03.35** — Course Schedule — `Topological sort` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/course-schedule/)
- [ ] **03.36** — Course Schedule II — `Topological sort` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/course-schedule-ii/)
- [✅] **03.37** — Detect Cycle in Undirected Graph — `DFS / DSU` — *Practice* — [Practice: Codeforces](https://codeforces.com/problemset/problem/1702/E)
- [✅] **03.38** — Detect Cycle in Directed Graph — `DFS` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Detect+Cycle+in+Directed+Graph)
- [✅] **03.39** — Bipartite Graph — `BFS / DFS` — *Practice* — [Practice: Codeforces](https://codeforces.com/problemset/problem/1702/E)
- [✅] **03.40** — Shortest Path in Unweighted Graph — `BFS` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Shortest+Path+in+Unweighted+Graph)
- [ ] **03.41** — Dijkstra Shortest Path — `Priority queue` — *Practice* — [Practice: Codeforces](https://codeforces.com/problemset/problem/20/C)
- [ ] **03.42** — Bellman-Ford — `Shortest path` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Bellman-Ford)
- [ ] **03.43** — Floyd-Warshall — `All-pairs shortest path` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Floyd-Warshall)
- [ ] **03.44** — Minimum Spanning Tree - Kruskal — `DSU` — *Practice* — [Practice: Codeforces](https://codeforces.com/problemset/problem/25/D)
- [ ] **03.45** — Minimum Spanning Tree - Prim — `Heap` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Minimum+Spanning+Tree+-+Prim)
- [ ] **03.46**  Number of Provinces — `DSU / DFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/number-of-provinces/)
- [ ] **03.47** — Network Delay Time — `Dijkstra` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/network-delay-time/)
- [ ] **03.48** — Word Ladder — `BFS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/word-ladder/)
- [ ] **03.49** — Articulation Points — `DFS` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Articulation+Points)
- [ ] **03.50** — Bridges in Graph — `Tarjan DFS` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Bridges+in+Graph)

## 04 — Dynamic Programming, Recursion, Backtracking & Bit Manipulation

- [ ] **04.01** — Knapsack — `Dynamic programming` — *PYQ/Official-style* — [Practice: LeetCode](https://leetcode.com/problems/partition-equal-subset-sum/)
- [ ] **04.02** — Fibonacci / memoization — `Dynamic programming` — *PYQ/Official-style* — [Practice: LeetCode](https://leetcode.com/problems/fibonacci-number/)
- [ ] **04.03** — Palindromic Subsequence — `2D DP` — *PYQ/Official-style* — [Practice: LeetCode](https://leetcode.com/problems/longest-palindromic-subsequence/)
- [ ] **04.04** — Longest Common Substring — `2D DP` — *PYQ/Official-style* — [Practice: LeetCode](https://leetcode.com/problems/maximum-length-of-repeated-subarray/)
- [ ] **04.05** — Dijkstra's Algorithm — `Shortest path` — *PYQ/Official-style* — [Practice: LeetCode](https://leetcode.com/problems/network-delay-time/)
- [ ] **04.06** — Longest Common Subsequence — `2D DP` — *PYQ-style* — [Practice: LeetCode](https://leetcode.com/problems/longest-common-subsequence/)
- [ ] **04.07** — Max XOR-Sum in Range — `Bit manipulation / greedy` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Max+XOR-Sum+in+Range)
- [ ] **04.08** — Max XOR of Half-Sized Subset — `Bit manipulation` — *PYQ-style* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Max+XOR+of+Half-Sized+Subset)
- [ ] **04.09** — Climbing Stairs — `1D DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/climbing-stairs/)
- [ ] **04.10** — House Robber — `1D DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/house-robber/)
- [ ] **04.11** — House Robber II — `DP on circle` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/house-robber-ii/)
- [ ] **04.12** — Coin Change — `Unbounded knapsack` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/coin-change/)
- [ ] **04.13** — Coin Change II — `Counting DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/coin-change-2/)
- [ ] **04.14** — Subset Sum — `0/1 knapsack` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Subset+Sum)
- [ ] **04.15** — Partition Equal Subset Sum — `0/1 DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/partition-equal-subset-sum/)
- [ ] **04.16** — Minimum Subset Sum Difference — `Knapsack DP` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Minimum+Subset+Sum+Difference)
- [ ] **04.17** — Count Subsets with Given Sum — `Counting DP` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Count+Subsets+with+Given+Sum)
- [ ] **04.18** — Target Sum — `Subset DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/target-sum/)
- [ ] **04.19** — 0/1 Knapsack — `Knapsack DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/partition-equal-subset-sum/)
- [ ] **04.20** — Unbounded Knapsack — `Knapsack DP` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Unbounded+Knapsack)
- [ ] **04.21** — Rod Cutting — `Unbounded DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/unbounded-knapsack/)
- [ ] **04.22** — Longest Increasing Subsequence — `LIS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-increasing-subsequence/)
- [ ] **04.23** — Longest Decreasing Subsequence — `LDS` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Longest+Decreasing+Subsequence)
- [ ] **04.24** — Maximum Sum Increasing Subsequence — `LIS DP` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Maximum+Sum+Increasing+Subsequence)
- [ ] **04.25** — Number of LIS — `LIS DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/number-of-longest-increasing-subsequence/)
- [ ] **04.26** — Russian Doll Envelopes — `LIS + sorting` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/russian-doll-envelopes/)
- [ ] **04.27** — Longest Bitonic Subsequence — `LIS/LDS` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/longest-mountain-in-array/)
- [ ] **04.28** — Edit Distance — `2D DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/edit-distance/)
- [ ] **04.29** — Distinct Subsequences — `2D DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/distinct-subsequences/)
- [ ] **04.30** — Interleaving String — `2D DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/interleaving-string/)
- [ ] **04.31** — Word Break — `String DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/word-break/)
- [ ] **04.32** — Palindrome Partitioning II — `Interval DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/palindrome-partitioning-ii/)
- [ ] **04.33** — Longest Palindromic Subsequence — `2D DP` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Longest+Palindromic+Subsequence)
- [ ] **04.34** — Minimum Insertions for Palindrome — `2D DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-insertion-steps-to-make-a-string-palindrome/)
- [ ] **04.35** — Matrix Chain Multiplication — `Interval DP` — *Practice* — [Practice: GFG search](https://www.geeksforgeeks.org/search/?q=Matrix+Chain+Multiplication)
- [ ] **04.36** — Burst Balloons — `Interval DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/burst-balloons/)
- [ ] **04.37** — Unique Paths — `Grid DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/unique-paths/)
- [ ] **04.38** — Unique Paths II — `Grid DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/unique-paths-ii/)
- [ ] **04.39** — Minimum Path Sum — `Grid DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-path-sum/)
- [ ] **04.40** — Triangle Minimum Path — `Grid DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/triangle/)
- [ ] **04.41** — Maximum Falling Path Sum — `Grid DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/minimum-falling-path-sum/)
- [ ] **04.42** — Cherry Pickup — `Grid DP` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/cherry-pickup/)
- [ ] **04.43** — N-Queens — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/n-queens/)
- [ ] **04.44** — Sudoku Solver — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/sudoku-solver/)
- [ ] **04.45** — Generate Parentheses — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/generate-parentheses/)
- [ ] **04.46** — Combination Sum — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/combination-sum/)
- [ ] **04.47** — Permutations — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/permutations/)
- [ ] **04.48** — Subsets — `Backtracking` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/subsets/)
- [ ] **04.49** — Single Number — `XOR` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/single-number/)
- [ ] **04.50** — Counting Set Bits — `Bit manipulation` — *Practice* — [Practice: LeetCode](https://leetcode.com/problems/counting-bits/)

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
