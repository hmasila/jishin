# 507. Perfect Number

<br />A <a href="https://en.wikipedia.org/wiki/Perfect_number" target="_blank">**perfect number**</a> is a **positive integer** that is equal to the sum of its **positive divisors**, excluding the number itself. A **divisor** of an integer `x` is an integer that can divide `x` evenly.<br />
<br />Given an integer `n`, return `true`<em> if </em>`n`<em> is a perfect number, otherwise return </em>`false`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: num = 28
Output: true
Explanation: 28 = 1 + 2 + 4 + 7 + 14
1, 2, 4, 7, and 14 are all divisors of 28.
```
<br />**Example 2:**<br />
```
Input: num = 7
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= num <;= 10<sup>8</sup>`