# 637. Average of Levels in Binary Tree

Given the `root` of a binary tree, return <em>the average value of the nodes on each level in the form of an array</em>. Answers within `10<sup>-5</sup>` of the actual answer will be accepted.
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/03/09/avg1-tree.jpg" style="width:277px;height:302px"/>
```
Input: root = [3,9,20,null,null,15,7]
Output: [3.00000,14.50000,11.00000]
Explanation: The average value of nodes on level 0 is 3, on level 1 is 14.5, and on level 2 is 11.
Hence return [3, 14.5, 11].
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/03/09/avg2-tree.jpg" style="width:292px;height:302px"/>
```
Input: root = [3,9,20,15,7]
Output: [3.00000,14.50000,11.00000]
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 10<sup>4</sup>]`.

* `-2<sup>31</sup> <;= Node.val <;= 2<sup>31</sup> - 1`