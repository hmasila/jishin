# 566. Reshape the Matrix

<br />In MATLAB, there is a handy function called `reshape` which can reshape an `m x n` matrix into a new one with a different size `r x c` keeping its original data.<br />
<br />You are given an `m x n` matrix `mat` and two integers `r` and `c` representing the number of rows and the number of columns of the wanted reshaped matrix.<br />
<br />The reshaped matrix should be filled with all the elements of the original matrix in the same row-traversing order as they were.<br />
<br />If the `reshape` operation with given parameters is possible and legal, output the new reshaped matrix; Otherwise, output the original matrix.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/04/24/reshape1-grid.jpg" style="width:613px;height:173px"/>
```
Input: mat = [[1,2],[3,4]], r = 1, c = 4
Output: [[1,2,3,4]]
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/04/24/reshape2-grid.jpg" style="width:453px;height:173px"/>
```
Input: mat = [[1,2],[3,4]], r = 2, c = 4
Output: [[1,2],[3,4]]
```
<br /> <br />
<br />**Constraints:**<br />

* `m == mat.length`

* `n == mat[i].length`

* `1 <;= m, n <;= 100`

* `-1000 <;= mat[i][j] <;= 1000`

* `1 <;= r, c <;= 300`