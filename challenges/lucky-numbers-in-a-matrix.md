# 1380. Lucky Numbers in a Matrix

<br />Given an `m x n` matrix of **distinct **numbers, return <em>all **lucky numbers** in the matrix in **any **order</em>.<br />
<br />A **lucky number** is an element of the matrix such that it is the minimum element in its row and maximum in its column.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: matrix = [[3,7,8],[9,11,13],[15,16,17]]
Output: [15]
Explanation: 15 is the only lucky number since it is the minimum in its row and the maximum in its column.
```
<br />**Example 2:**<br />
```
Input: matrix = [[1,10,4,2],[9,3,8,7],[15,16,17,12]]
Output: [12]
Explanation: 12 is the only lucky number since it is the minimum in its row and the maximum in its column.
```
<br />**Example 3:**<br />
```
Input: matrix = [[7,8],[1,2]]
Output: [7]
Explanation: 7 is the only lucky number since it is the minimum in its row and the maximum in its column.
```
<br /> <br />
<br />**Constraints:**<br />

* `m == mat.length`

* `n == mat[i].length`

* `1 <;= n, m <;= 50`

* `1 <;= matrix[i][j] <;= 10<sup>5</sup>`.

* All elements in the matrix are distinct.