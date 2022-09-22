# 501. Find Mode in Binary Search Tree

<br />Given the `root` of a binary search tree (BST) with duplicates, return <em>all the <a href="https://en.wikipedia.org/wiki/Mode_(statistics)" target="_blank">mode(s)</a> (i.e., the most frequently occurred element) in it</em>.<br />
<br />If the tree has more than one mode, return them in **any order**.<br />
<br />Assume a BST is defined as follows:<br />

* The left subtree of a node contains only nodes with keys **less than or equal to** the node's key.

* The right subtree of a node contains only nodes with keys **greater than or equal to** the node's key.

* Both the left and right subtrees must also be binary search trees.


<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/03/11/mode-tree.jpg" style="width:142px;height:222px"/>
```
Input: root = [1,null,2,2]
Output: [2]
```
<br />**Example 2:**<br />
```
Input: root = [0]
Output: [0]
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 10<sup>4</sup>]`.

* `-10<sup>5</sup> <;= Node.val <;= 10<sup>5</sup>`


<br /> <br />
**Follow up:** Could you do that without using any extra space? (Assume that the implicit stack space incurred due to recursion does not count).