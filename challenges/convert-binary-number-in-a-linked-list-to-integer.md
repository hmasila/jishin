# 1290. Convert Binary Number in a Linked List to Integer

<br />Given `head` which is a reference node to a singly-linked list. The value of each node in the linked list is either `0` or `1`. The linked list holds the binary representation of a number.<br />
<br />Return the <em>decimal value</em> of the number in the linked list.<br />
<br />The **most significant bit** is at the head of the linked list.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/12/05/graph-1.png" style="width:426px;height:108px"/>
```
Input: head = [1,0,1]
Output: 5
Explanation: (101) in base 2 = (5) in base 10
```
<br />**Example 2:**<br />
```
Input: head = [0]
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* The Linked List is not empty.

* Number of nodes will not exceed `30`.

* Each node's value is either `0` or `1`.