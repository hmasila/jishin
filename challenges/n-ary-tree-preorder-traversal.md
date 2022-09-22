# 589. N-ary Tree Preorder Traversal

<br />Given the `root` of an n-ary tree, return <em>the preorder traversal of its nodes' values</em>.<br />
<br />Nary-Tree input serialization is represented in their level order traversal. Each group of children is separated by the null value (See examples)<br />
<br /> <br />
<br />**Example 1:**<br />
<br /><img src="https://assets.leetcode.com/uploads/2018/10/12/narytreeexample.png" style="width:100%;max-width:300px"/><br />
```
Input: root = [1,null,3,2,4,null,5,6]
Output: [1,3,5,6,2,4]
```
<br />**Example 2:**<br />
<br /><img alt="" src="https://assets.leetcode.com/uploads/2019/11/08/sample_4_964.png" style="width:296px;height:241px"/><br />
```
Input: root = [1,null,2,3,4,5,null,null,6,7,null,8,null,9,10,null,null,11,null,12,null,13,null,null,14]
Output: [1,2,3,6,7,11,14,4,8,12,5,9,13,10]
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the tree is in the range `[0, 10<sup>4</sup>]`.

* `0 <;= Node.val <;= 10<sup>4</sup>`

* The height of the n-ary tree is less than or equal to `1000`.


<br /> <br />
<br />**Follow up:** Recursive solution is trivial, could you do it iteratively?<br />