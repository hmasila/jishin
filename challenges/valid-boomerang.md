# 1037. Valid Boomerang

<br />Given an array `points` where `points[i] = [x<sub>i</sub>, y<sub>i</sub>]` represents a point on the **X-Y** plane, return `true` <em>if these points are a **boomerang**</em>.<br />
<br />A **boomerang** is a set of three points that are **all distinct** and **not in a straight line**.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: points = [[1,1],[2,3],[3,2]]
Output: true
```<br />**Example 2:**<br />
```
Input: points = [[1,1],[2,2],[3,3]]
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `points.length == 3`

* `points[i].length == 2`

* `0 <;= x<sub>i</sub>, y<sub>i</sub> <;= 100`