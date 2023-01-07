# 119. Pascal's Triangle II

<br />Given an integer `rowIndex`, return the `rowIndex<sup>th</sup>` (**0-indexed**) row of the **Pascal's triangle**.<br />
<br />In **Pascal's triangle**, each number is the sum of the two numbers directly above it as shown:<br />
<img alt="" src="https://upload.wikimedia.org/wikipedia/commons/0/0d/PascalTriangleAnimated2.gif" style="height:240px;width:260px"/>
<br /> <br />
<br />**Example 1:**<br />
```
Input: rowIndex = 3
Output: [1,3,3,1]
```<br />**Example 2:**<br />
```
Input: rowIndex = 0
Output: [1]
```<br />**Example 3:**<br />
```
Input: rowIndex = 1
Output: [1,1]
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= rowIndex <;= 33`


<br /> <br />
<br />**Follow up:** Could you optimize your algorithm to use only `O(rowIndex)` extra space?<br />