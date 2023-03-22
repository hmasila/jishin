# 671. Second Minimum Node In a Binary Tree

<br />Given a non-empty special binary tree consisting of nodes with the non-negative value, where each node in this tree has exactly `two` or `zero` sub-node. If the node has two sub-nodes, then this node's value is the smaller value among its two sub-nodes. More formally, the property `root.val = min(root.left.val, root.right.val)` always holds.<br />
<br />Given such a binary tree, you need to output the <b>second minimum</b> value in the set made of all the nodes' value in the whole tree.<br />
<br />If no such second minimum value exists, output -1 instead.<br />
<br /> <br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/15/smbt1.jpg" style="width:431px;height:302px"/>
```
Input: root = [2,2,5,null,null,5,7]
Output: 5
Explanation: The smallest value is 2, the second smallest value is 5.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/15/smbt2.jpg" style="width:321px;height:182px"/>
```
Input: root = [2,2,2]
Output: -1
Explanation: The smallest value is 2, but there isn't any second smallest value.
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 25]`.

* `1 <;= Node.val <;= 2<sup>31</sup> - 1`

* `root.val == min(root.left.val, root.right.val)` for each internal node of the tree.