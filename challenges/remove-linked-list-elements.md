# 203. Remove Linked List Elements

<br />Given the `head` of a linked list and an integer `val`, remove all the nodes of the linked list that has `Node.val == val`, and return <em>the new head</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/03/06/removelinked-list.jpg" style="width:500px;height:142px"/>
```
Input: head = [1,2,6,3,4,5,6], val = 6
Output: [1,2,3,4,5]
```
<br />**Example 2:**<br />
```
Input: head = [], val = 1
Output: []
```
<br />**Example 3:**<br />
```
Input: head = [7,7,7,7], val = 7
Output: []
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the list is in the range `[0, 10<sup>4</sup>]`.

* `1 <;= Node.val <;= 50`

* `0 <;= val <;= 50`