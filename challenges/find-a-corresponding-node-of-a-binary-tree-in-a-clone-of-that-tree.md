# 1379. Find a Corresponding Node of a Binary Tree in a Clone of That Tree

<br />Given two binary trees `original` and `cloned` and given a reference to a node `target` in the original tree.<br />
<br />The `cloned` tree is a **copy of** the `original` tree.<br />
<br />Return <em>a reference to the same node</em> in the `cloned` tree.<br />
<br />**Note** that you are **not allowed** to change any of the two trees or the `target` node and the answer **must be** a reference to a node in the `cloned` tree.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/02/21/e1.png" style="width:544px;height:426px"/>
```
Input: tree = [7,4,3,null,null,6,19], target = 3
Output: 3
Explanation: In all examples the original and cloned trees are shown. The target node is a green node from the original tree. The answer is the yellow node from the cloned tree.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/02/21/e2.png" style="width:221px;height:159px"/>
```
Input: tree = [7], target =  7
Output: 7
```
<br />**Example 3:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/02/21/e3.png" style="width:459px;height:486px"/>
```
Input: tree = [8,null,6,null,5,null,4,null,3,null,2,null,1], target = 4
Output: 4
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the `tree` is in the range `[1, 10<sup>4</sup>]`.

* The values of the nodes of the `tree` are unique.

* `target` node is a node from the `original` tree and is not `null`.


<br /> <br />
<br />**Follow up:** Could you solve the problem if repeated values on the tree are allowed?<br />