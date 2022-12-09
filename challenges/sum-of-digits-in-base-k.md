# 1837. Sum of Digits in Base K

<br />Given an integer `n` (in base `10`) and a base `k`, return <em>the **sum** of the digits of </em>`n`<em> **after** converting </em>`n`<em> from base </em>`10`<em> to base </em>`k`.<br />
<br />After converting, each digit should be interpreted as a base `10` number, and the sum should be returned in base `10`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 34, k = 6
Output: 9
**Explanation: **34 (base 10) expressed in base 6 is 54. 5 + 4 = 9.
```
<br />**Example 2:**<br />
```
Input: n = 10, k = 10
Output: 1
**Explanation: **n is already in base 10. 1 + 0 = 1.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 100`

* `2 <;= k <;= 10`