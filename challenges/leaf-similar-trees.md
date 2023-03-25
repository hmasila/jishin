# 872. Leaf-Similar Trees

<br />Consider all the leaves of a binary tree, from left to right order, the values of those leaves form a **leaf value sequence**<em>.</em><br />
<br /><img alt="" src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/07/16/tree.png" style="width:400px;height:336px"/><br />
<br />For example, in the given tree above, the leaf value sequence is `(6, 7, 4, 9, 8)`.<br />
<br />Two binary trees are considered <em>leaf-similar</em> if their leaf value sequence is the same.<br />
<br />Return `true` if and only if the two given trees with head nodes `root1` and `root2` are leaf-similar.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/03/leaf-similar-1.jpg" style="width:600px;height:237px"/>
```
Input: root1 = [3,5,1,6,2,9,8,null,null,7,4], root2 = [3,5,1,6,7,4,2,null,null,null,null,null,null,9,8]
Output: true
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/09/03/leaf-similar-2.jpg" style="width:300px;height:110px"/>
```
Input: root1 = [1,2,3], root2 = [1,3,2]
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in each tree will be in the range `[1, 200]`.

* Both of the given trees will have values in the range `[0, 200]`.