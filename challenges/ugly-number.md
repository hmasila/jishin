# 263. Ugly Number

<br />An **ugly number** is a positive integer whose prime factors are limited to `2`, `3`, and `5`.<br />
<br />Given an integer `n`, return `true` <em>if</em> `n` <em>is an **ugly number**</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 6
Output: true
Explanation: 6 = 2 × 3
```
<br />**Example 2:**<br />
```
Input: n = 1
Output: true
Explanation: 1 has no prime factors, therefore all of its prime factors are limited to 2, 3, and 5.
```
<br />**Example 3:**<br />
```
Input: n = 14
Output: false
Explanation: 14 is not ugly since it includes the prime factor 7.
```
<br /> <br />
<br />**Constraints:**<br />

* `-2<sup>31</sup> <;= n <;= 2<sup>31</sup> - 1`