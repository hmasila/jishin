# 110. Balanced Binary Tree

<br />Given a binary tree, determine if it is <span class="cursor-pointer relative text-dark-blue-s text-sm" data-keyword="height-balanced">**height-balanced**</span>.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/06/balance_1.jpg" style="width: 342px; height: 221px;"/>
```
Input: root = [3,9,20,null,null,15,7]
Output: true
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/06/balance_2.jpg" style="width: 452px; height: 301px;"/>
```
Input: root = [1,2,2,3,3,null,null,4,4]
Output: false
```
<br />**Example 3:**<br />
```
Input: root = []
Output: true
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[0, 5000]`.

* `-10<sup>4</sup> <;= Node.val <;= 10<sup>4</sup>`