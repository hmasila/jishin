# 572. Subtree of Another Tree

<br />Given the roots of two binary trees `root` and `subRoot`, return `true` if there is a subtree of `root` with the same structure and node values of` subRoot` and `false` otherwise.<br />
<br />A subtree of a binary tree `tree` is a tree that consists of a node in `tree` and all of this node's descendants. The tree `tree` could also be considered as a subtree of itself.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/04/28/subtree1-tree.jpg" style="width:532px;height:400px"/>
```
Input: root = [3,4,5,1,2], subRoot = [4,1,2]
Output: true
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/04/28/subtree2-tree.jpg" style="width:502px;height:458px"/>
```
Input: root = [3,4,5,1,2,null,null,null,null,0], subRoot = [4,1,2]
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the `root` tree is in the range `[1, 2000]`.

* The number of nodes in the `subRoot` tree is in the range `[1, 1000]`.

* `-10<sup>4</sup> <;= root.val <;= 10<sup>4</sup>`

* `-10<sup>4</sup> <;= subRoot.val <;= 10<sup>4</sup>`