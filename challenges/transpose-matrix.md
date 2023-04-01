# 867. Transpose Matrix

<br />Given a 2D integer array `matrix`, return <em>the **transpose** of</em> `matrix`.<br />
<br />The **transpose** of a matrix is the matrix flipped over its main diagonal, switching the matrix's row and column indices.<br />
<br /><img alt="" src="https://assets.leetcode.com/uploads/2021/02/10/hint_transpose.png" style="width:600px;height:197px"/><br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: matrix = [[1,2,3],[4,5,6],[7,8,9]]
Output: [[1,4,7],[2,5,8],[3,6,9]]
```
<br />**Example 2:**<br />
```
Input: matrix = [[1,2,3],[4,5,6]]
Output: [[1,4],[2,5],[3,6]]
```
<br /> <br />
<br />**Constraints:**<br />

* `m == matrix.length`

* `n == matrix[i].length`

* `1 <;= m, n <;= 1000`

* `1 <;= m * n <;= 10<sup>5</sup>`

* `-10<sup>9</sup> <;= matrix[i][j] <;= 10<sup>9</sup>`