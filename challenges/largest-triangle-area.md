# 812. Largest Triangle Area

<br />Given an array of points on the **X-Y** plane `points` where `points[i] = [x<sub>i</sub>, y<sub>i</sub>]`, return <em>the area of the largest triangle that can be formed by any three different points</em>. Answers within `10<sup>-5</sup>` of the actual answer will be accepted.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://s3-lc-upload.s3.amazonaws.com/uploads/2018/04/04/1027.png" style="height:369px;width:450px"/>
```
Input: points = [[0,0],[0,1],[1,0],[0,2],[2,0]]
Output: 2.00000
Explanation: The five points are shown in the above figure. The red triangle is the largest.
```
<br />**Example 2:**<br />
```
Input: points = [[1,0],[0,0],[0,1]]
Output: 0.50000
```
<br /> <br />
<br />**Constraints:**<br />

* `3 <;= points.length <;= 50`

* `-50 <;= x<sub>i</sub>, y<sub>i</sub> <;= 50`

* All the given points are **unique**.