# 965. Univalued Binary Tree

<br />A binary tree is **uni-valued** if every node in the tree has the same value.<br />
<br />Given the `root` of a binary tree, return `true`<em> if the given tree is **uni-valued**, or </em>`false`<em> otherwise.</em><br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2018/12/28/unival_bst_1.png" style="width:265px;height:172px"/>
```
Input: root = [1,1,1,1,1,null,1]
Output: true
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2018/12/28/unival_bst_2.png" style="width:198px;height:169px"/>
```
Input: root = [2,2,2,5,2]
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 100]`.

* `0 <;= Node.val <; 100`