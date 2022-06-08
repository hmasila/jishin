# 1317. Convert Integer to the Sum of Two No-Zero Integers

<br />**No-Zero integer** is a positive integer that **does not contain any `0`** in its decimal representation.<br />
<br />Given an integer `n`, return <em>a list of two integers</em> `[a, b]` <em>where</em>:<br />

* `a` and `b` are **No-Zero integers**.

* `a + b = n`


<br />The test cases are generated so that there is at least one valid solution. If there are many valid solutions, you can return any of them.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 2
Output: [1,1]
Explanation: Let a = 1 and b = 1.
Both a and b are no-zero integers, and a + b = 2 = n.
```
<br />**Example 2:**<br />
```
Input: n = 11
Output: [2,9]
Explanation: Let a = 2 and b = 9.
Both a and b are no-zero integers, and a + b = 9 = n.
Note that there are other valid answers as [8, 3] that can be accepted.
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= n <;= 10<sup>4</sup>`