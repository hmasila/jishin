# 700. Search in a Binary Search Tree

<br />You are given the `root` of a binary search tree (BST) and an integer `val`.<br />
<br />Find the node in the BST that the node's value equals `val` and return the subtree rooted with that node. If such a node does not exist, return `null`.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/12/tree1.jpg" style="width:422px;height:302px"/>
```
Input: root = [4,2,7,1,3], val = 2
Output: [2,1,3]
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/12/tree2.jpg" style="width:422px;height:302px"/>
```
Input: root = [4,2,7,1,3], val = 5
Output: []
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 5000]`.

* `1 <;= Node.val <;= 10<sup>7</sup>`

* `root` is a binary search tree.

* `1 <;= val <;= 10<sup>7</sup>`