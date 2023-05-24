# 1232. Check If It Is a Straight Line

<br />You are given an array `coordinates`, `coordinates[i] = [x, y]`, where `[x, y]` represents the coordinate of a point. Check if these points make a straight line in the XY plane.<br />
<br /> <br />
<br /> <br />
<br />**Example 1:**<br />
<br /><img alt="" src="https://assets.leetcode.com/uploads/2019/10/15/untitled-diagram-2.jpg" style="width:336px;height:336px"/><br />
```
Input: coordinates = [[1,2],[2,3],[3,4],[4,5],[5,6],[6,7]]
Output: true
```
<br />**Example 2:**<br />
<br />**<img alt="" src="https://assets.leetcode.com/uploads/2019/10/09/untitled-diagram-1.jpg" style="width:348px;height:336px"/>**<br />
```
Input: coordinates = [[1,1],[2,2],[3,4],[4,5],[5,6],[7,7]]
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= coordinates.length <;= 1000`

* `coordinates[i].length == 2`

* `-10^4 <;= coordinates[i][0], coordinates[i][1] <;= 10^4`

* `coordinates` contains no duplicate point.