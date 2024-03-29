# 112. Path Sum

<br />Given the `root` of a binary tree and an integer `targetSum`, return `true` if the tree has a **root-to-leaf** path such that adding up all the values along the path equals `targetSum`.<br />
<br />A **leaf** is a node with no children.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/18/pathsum1.jpg" style="width:500px;height:356px"/>
```
Input: root = [5,4,8,11,null,13,4,7,2,null,null,null,1], targetSum = 22
Output: true
Explanation: The root-to-leaf path with the target sum is shown.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/18/pathsum2.jpg"/>
```
Input: root = [1,2,3], targetSum = 5
Output: false
Explanation: There two root-to-leaf paths in the tree:
(1 -->; 2): The sum is 3.
(1 -->; 3): The sum is 4.
There is no root-to-leaf path with sum = 5.
```
<br />**Example 3:**<br />
```
Input: root = [], targetSum = 0
Output: false
Explanation: Since the tree is empty, there are no root-to-leaf paths.
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[0, 5000]`.

* `-1000 <;= Node.val <;= 1000`

* `-1000 <;= targetSum <;= 1000`