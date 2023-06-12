# 606. Construct String from Binary Tree

<br />Given the `root` of a binary tree, construct a string consisting of parenthesis and integers from a binary tree with the preorder traversal way, and return it.<br />
<br />Omit all the empty parenthesis pairs that do not affect the one-to-one mapping relationship between the string and the original binary tree.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/05/03/cons1-tree.jpg" style="width:292px;height:301px"/>
```
Input: root = [1,2,3,4]
Output: "1(2(4))(3)"
Explanation: Originally, it needs to be "1(2(4)())(3()())", but you need to omit all the unnecessary empty parenthesis pairs. And it will be "1(2(4))(3)"
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/05/03/cons2-tree.jpg" style="width:207px;height:293px"/>
```
Input: root = [1,2,3,null,4]
Output: "1(2()(4))(3)"
Explanation: Almost the same as the first example, except we cannot omit the first parenthesis pair to break the one-to-one mapping relationship between the input and the output.
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[1, 10<sup>4</sup>]`.

* `-1000 <;= Node.val <;= 1000`