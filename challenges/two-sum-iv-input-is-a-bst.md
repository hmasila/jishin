# 653. Two Sum IV - Input is a BST

<br />Given the `root` of a binary search tree and an integer `k`, return `true` <em>if there exist two elements in the BST such that their sum is equal to</em> `k`, <em>or</em> `false` <em>otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/21/sum_tree_1.jpg" style="width:400px;height:229px"/>
```
Input: root = [5,3,6,2,4,null,7], k = 9
Output: true
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/21/sum_tree_2.jpg" style="width:400px;height:229px"/>
```
Input: root = [5,3,6,2,4,null,7], k = 28
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 10<sup>4</sup>]`.

* `-10<sup>4</sup> <;= Node.val <;= 10<sup>4</sup>`

* `root` is guaranteed to be a **valid** binary search tree.

* `-10<sup>5</sup> <;= k <;= 10<sup>5</sup>`