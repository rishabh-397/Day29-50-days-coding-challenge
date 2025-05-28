# Day29-50-days-coding-challenge

## Problem 1: Sum of Left Leaves
- Goal: Find the sum of all left leaf nodes in a binary tree.
- Approach: Use recursive DFS or BFS to identify left leaves and accumulate their values.
- Time Complexity: O(N), where N is the number of nodes in the tree.
- Edge cases: Trees with no left leaves or only root nodes.

Example:
Input: root = [3,9,20,null,null,15,7]

Output: 24

## Problem 2: Kth Largest Element in an Array
- Goal: Return the kth largest element in the array without sorting.
- Approach: Use a Min-Heap of size k to efficiently track the kth largest.
- Time Complexity: O(n log k)
- Space Complexity: O(k)
- Edge cases: k = 1 (max element), k = length of array (min element), repeated elements.

Example:
Input: nums = [3,2,1,5,6,4], k = 2

Output: 5

This solution is part of the #DrGViswanathanChallenge for 50 days of coding.

Stay tuned for Day 30!
