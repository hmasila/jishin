# 441. Arranging Coins

<br />You have `n` coins and you want to build a staircase with these coins. The staircase consists of `k` rows where the `i<sup>th</sup>` row has exactly `i` coins. The last row of the staircase **may be** incomplete.<br />
<br />Given the integer `n`, return <em>the number of **complete rows** of the staircase you will build</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/04/09/arrangecoins1-grid.jpg" style="width:253px;height:253px"/>
```
Input: n = 5
Output: 2
Explanation: Because the 3<sup>rd</sup> row is incomplete, we return 2.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/04/09/arrangecoins2-grid.jpg" style="width:333px;height:333px"/>
```
Input: n = 8
Output: 3
Explanation: Because the 4<sup>th</sup> row is incomplete, we return 3.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 2<sup>31</sup> - 1`