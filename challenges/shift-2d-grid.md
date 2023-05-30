# 1260. Shift 2D Grid

<br />Given a 2D `grid` of size `m x n` and an integer `k`. You need to shift the `grid` `k` times.<br />
<br />In one shift operation:<br />

* Element at `grid[i][j]` moves to `grid[i][j + 1]`.

* Element at `grid[i][n - 1]` moves to `grid[i + 1][0]`.

* Element at `grid[m - 1][n - 1]` moves to `grid[0][0]`.


<br />Return the <em>2D grid</em> after applying shift operation `k` times.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/11/05/e1.png" style="width:400px;height:178px"/>
```
Input: `grid` = [[1,2,3],[4,5,6],[7,8,9]], k = 1
Output: [[9,1,2],[3,4,5],[6,7,8]]
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/11/05/e2.png" style="width:400px;height:166px"/>
```
Input: `grid` = [[3,8,1,9],[19,7,2,5],[4,6,11,10],[12,0,21,13]], k = 4
Output: [[12,0,21,13],[3,8,1,9],[19,7,2,5],[4,6,11,10]]
```
<br />**Example 3:**<br />
```
Input: `grid` = [[1,2,3],[4,5,6],[7,8,9]], k = 9
Output: [[1,2,3],[4,5,6],[7,8,9]]
```
<br /> <br />
<br />**Constraints:**<br />

* `m == grid.length`

* `n == grid[i].length`

* `1 <;= m <;= 50`

* `1 <;= n <;= 50`

* `-1000 <;= grid[i][j] <;= 1000`

* `0 <;= k <;= 100`