# 509. Fibonacci Number

<br />The <b>Fibonacci numbers</b>, commonly denoted `F(n)` form a sequence, called the <b>Fibonacci sequence</b>, such that each number is the sum of the two preceding ones, starting from `0` and `1`. That is,<br />
```F(0) = 0, F(1) = 1
F(n) = F(n - 1) + F(n - 2), for n >; 1.
```
<br />Given `n`, calculate `F(n)`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 2
Output: 1
Explanation: F(2) = F(1) + F(0) = 1 + 0 = 1.
```
<br />**Example 2:**<br />
```
Input: n = 3
Output: 2
Explanation: F(3) = F(2) + F(1) = 1 + 1 = 2.
```
<br />**Example 3:**<br />
```
Input: n = 4
Output: 3
Explanation: F(4) = F(3) + F(2) = 2 + 1 = 3.
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= n <;= 30`