# 993. Cousins in Binary Tree

<br />Given the `root` of a binary tree with unique values and the values of two different nodes of the tree `x` and `y`, return `true` <em>if the nodes corresponding to the values </em>`x`<em> and </em>`y`<em> in the tree are **cousins**, or </em>`false`<em> otherwise.</em><br />
<br />Two nodes of a binary tree are **cousins** if they have the same depth with different parents.<br />
<br />Note that in a binary tree, the root node is at the depth `0`, and children of each depth `k` node are at the depth `k + 1`.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/02/12/q1248-01.png" style="width:304px;height:270px"/>
```
Input: root = [1,2,3,4], x = 4, y = 3
Output: false
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/02/12/q1248-02.png" style="width:334px;height:266px"/>
```
Input: root = [1,2,3,null,4,null,5], x = 5, y = 4
Output: true
```
<br />**Example 3:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/02/13/q1248-03.png" style="width:267px;height:258px"/>
```
Input: root = [1,2,3,null,4], x = 2, y = 3
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[2, 100]`.

* `1 <;= Node.val <;= 100`

* Each node has a **unique** value.

* `x != y`

* `x` and `y` are exist in the tree.