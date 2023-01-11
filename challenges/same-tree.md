# 100. Same Tree

<br />Given the roots of two binary trees `p` and `q`, write a function to check if they are the same or not.<br />
<br />Two binary trees are considered the same if they are structurally identical, and the nodes have the same value.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/12/20/ex1.jpg" style="width:622px;height:182px"/>
```
Input: p = [1,2,3], q = [1,2,3]
Output: true
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/12/20/ex2.jpg" style="width:382px;height:182px"/>
```
Input: p = [1,2], q = [1,null,2]
Output: false
```
<br />**Example 3:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/12/20/ex3.jpg" style="width:622px;height:182px"/>
```
Input: p = [1,2,1], q = [1,1,2]
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in both trees is in the range `[0, 100]`.

* `-10<sup>4</sup> <;= Node.val <;= 10<sup>4</sup>`