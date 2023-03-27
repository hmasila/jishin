# 876. Middle of the Linked List

<br />Given the `head` of a singly linked list, return <em>the middle node of the linked list</em>.<br />
<br />If there are two middle nodes, return **the second middle** node.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/07/23/lc-midlist1.jpg" style="width:544px;height:65px"/>
```
Input: head = [1,2,3,4,5]
Output: [3,4,5]
Explanation: The middle node of the list is node 3.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/07/23/lc-midlist2.jpg" style="width:664px;height:65px"/>
```
Input: head = [1,2,3,4,5,6]
Output: [4,5,6]
Explanation: Since the list has two middle nodes with values 3 and 4, we return the second one.
```
<br /> <br />
<br />**Constraints:**<br />

* The number of nodes in the list is in the range `[1, 100]`.

* `1 <;= Node.val <;= 100`