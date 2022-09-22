# 258. Add Digits

<br />Given an integer `num`, repeatedly add all its digits until the result has only one digit, and return it.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: num = 38
Output: 2
Explanation: The process is
38 -->; 3 + 8 -->; 11
11 -->; 1 + 1 -->; 2 
Since 2 has only one digit, return it.
```
<br />**Example 2:**<br />
```
Input: num = 0
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= num <;= 2<sup>31</sup> - 1`


<br /> <br />
<br />**Follow up:** Could you do it without any loop/recursion in `O(1)` runtime?<br />