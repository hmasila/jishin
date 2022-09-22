# 404. Sum of Left Leaves

<br />Given the `root` of a binary tree, return <em>the sum of all left leaves.</em><br />
<br />A **leaf** is a node with no children. A **left leaf** is a leaf that is the left child of another node.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/04/08/leftsum-tree.jpg" style="width:277px;height:302px"/>
```
Input: root = [3,9,20,null,null,15,7]
Output: 24
Explanation: There are two left leaves in the binary tree, with values 9 and 15 respectively.
```
<br />**Example 2:**<br />
```
Input: root = [1]
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 1000]`.

* `-1000 <;= Node.val <;= 1000`