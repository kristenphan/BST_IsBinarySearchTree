# BST: Is Binary Search Tree?

__Repository Description:__
<br/>
This repository stores the work as part of the Data Structures and Algorithms specialization courses by University California of San Diego. Course URL: https://www.coursera.org/learn/data-structures/. Code in this repository is written by myself, Kristen Phan.
<br/>
<br/>
__Assignment Description:__
<br/>
Task: You are given a binary tree with integers as its keys. You need to test whether it is a correct binary
search tree. The definition of the binary search tree is the following: for any node of the tree, if its
key is 𝑥, then for any node in its left subtree its key must be strictly less than 𝑥, and for any node in
its right subtree its key must be strictly greater than 𝑥. In other words, smaller elements are to the
left, and bigger elements are to the right. You need to check whether the given binary tree structure
satisfies this condition. You are guaranteed that the input contains a valid binary tree. That is, it is a
tree, and each node has at most two children. Note that testing the binary search tree condition for each node and every other node in its subtree will be too slow. A faster algorithm is required to meet the runtime limit for this assignment.
<br/>
<br/>
Input Format: The first line contains the number of vertices 𝑛. The vertices of the tree are numbered
from 0 to 𝑛 − 1. Vertex 0 is the root.
The next 𝑛 lines contain information about vertices 0, 1, ..., 𝑛−1 in order. Each of these lines contains
three integers 𝑘𝑒𝑦𝑖, 𝑙𝑒𝑓𝑡𝑖 and 𝑟𝑖𝑔ℎ𝑡𝑖 — 𝑘𝑒𝑦𝑖 is the key of the 𝑖-th vertex, 𝑙𝑒𝑓𝑡𝑖 is the index of the left
child of the 𝑖-th vertex, and 𝑟𝑖𝑔ℎ𝑡𝑖 is the index of the right child of the 𝑖-th vertex. If 𝑖 doesn’t have
left or right child (or both), the corresponding 𝑙𝑒𝑓𝑡𝑖 or 𝑟𝑖𝑔ℎ𝑡𝑖 (or both) will be equal to −1.
<br/>
<br/>
Constraints: 0 ≤ 𝑛 ≤ 105; −231 < 𝑘𝑒𝑦𝑖 < 231 − 1; −1 ≤ 𝑙𝑒𝑓𝑡𝑖, 𝑟𝑖𝑔ℎ𝑡𝑖 ≤ 𝑛 − 1. It is guaranteed that the
input represents a valid binary tree. In particular, if 𝑙𝑒𝑓𝑡𝑖 ̸= −1 and 𝑟𝑖𝑔ℎ𝑡𝑖 ̸= −1, then 𝑙𝑒𝑓𝑡𝑖 ̸= 𝑟𝑖𝑔ℎ𝑡𝑖.
Also, a vertex cannot be a child of two different vertices. Also, each vertex is a descendant of the root
vertex. All keys in the input will be different.
<br/>
<br/>
Output Format: If the given binary tree is a correct binary search tree (see the definition in the problem
description), output one word “CORRECT” (without quotes). Otherwise, output one word “INCORRECT”
(without quotes).
<br/>
<br/>
Time Limits: Python - 10 seconds
<br/>
<br/>
Memory Limit: 512MB.
<br/>
<br/>
__Disclaimer__: 
<br/>
If you're currently taking the same course, please refrain yourself from checking out this solution as it will be against Coursera's Honor Code and won’t do you any good. Plus, once you're worked your heart out and was able to solve a particularly difficult problem, a sense of confidence you gained from such experience is priceless :)
