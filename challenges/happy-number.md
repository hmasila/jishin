# 202. Happy Number

<br />Write an algorithm to determine if a number `n` is happy.<br />
<br />A **happy number** is a number defined by the following process:<br />

* Starting with any positive integer, replace the number by the sum of the squares of its digits.

* Repeat the process until the number equals 1 (where it will stay), or it **loops endlessly in a cycle** which does not include 1.

* Those numbers for which this process **ends in 1** are happy.


<br />Return `true` <em>if</em> `n` <em>is a happy number, and</em> `false` <em>if not</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 19
Output: true
Explanation:
1<sup>2</sup> + 9<sup>2</sup> = 82
8<sup>2</sup> + 2<sup>2</sup> = 68
6<sup>2</sup> + 8<sup>2</sup> = 100
1<sup>2</sup> + 0<sup>2</sup> + 0<sup>2</sup> = 1
```
<br />**Example 2:**<br />
```
Input: n = 2
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 2<sup>31</sup> - 1`