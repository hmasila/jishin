# 257. Binary Tree Paths

<br />Given the `root` of a binary tree, return <em>all root-to-leaf paths in **any order**</em>.<br />
<br />A **leaf** is a node with no children.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/03/12/paths-tree.jpg" style="width:207px;height:293px"/>
```
Input: root = [1,2,3,null,5]
Output: ["1->;2->;5","1->;3"]
```
<br />**Example 2:**<br />
```
Input: root = [1]
Output: ["1"]
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 100]`.

* `-100 <;= Node.val <;= 100`