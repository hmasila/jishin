# 543. Diameter of Binary Tree

<br />Given the `root` of a binary tree, return <em>the length of the **diameter** of the tree</em>.<br />
<br />The **diameter** of a binary tree is the **length** of the longest path between any two nodes in a tree. This path may or may not pass through the `root`.<br />
<br />The **length** of a path between two nodes is represented by the number of edges between them.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/03/06/diamtree.jpg" style="width:292px;height:302px"/>
```
Input: root = [1,2,3,4,5]
Output: 3
Explanation: 3 is the length of the path [4,2,1,3] or [5,2,1,3].
```
<br />**Example 2:**<br />
```
Input: root = [1,2]
Output: 1
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 10<sup>4</sup>]`.

* `-100 <;= Node.val <;= 100`