# 892. Surface Area of 3D Shapes

<br />You are given an `n x n` `grid` where you have placed some `1 x 1 x 1` cubes. Each value `v = grid[i][j]` represents a tower of `v` cubes placed on top of cell `(i, j)`.<br />
<br />After placing these cubes, you have decided to glue any directly adjacent cubes to each other, forming several irregular 3D shapes.<br />
<br />Return <em>the total surface area of the resulting shapes</em>.<br />
<br />**Note:** The bottom face of each shape counts toward its surface area.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/08/tmp-grid2.jpg" style="width:162px;height:162px"/>
```
Input: grid = [[1,2],[3,4]]
Output: 34
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/08/tmp-grid4.jpg" style="width:242px;height:242px"/>
```
Input: grid = [[1,1,1],[1,0,1],[1,1,1]]
Output: 32
```
<br />**Example 3:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/01/08/tmp-grid5.jpg" style="width:242px;height:242px"/>
```
Input: grid = [[2,2,2],[2,1,2],[2,2,2]]
Output: 46
```
<br /> <br />
<br />**Constraints:**<br />

* `n == grid.length == grid[i].length`

* `1 <;= n <;= 50`

* `0 <;= grid[i][j] <;= 50`