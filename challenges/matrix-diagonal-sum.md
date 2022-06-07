# 1572. Matrix Diagonal Sum

<br />Given a square matrix `mat`, return the sum of the matrix diagonals.<br />
<br />Only include the sum of all the elements on the primary diagonal and all the elements on the secondary diagonal that are not part of the primary diagonal.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/08/14/sample_1911.png" style="width:336px;height:174px"/>
```
Input: mat = [[**1**,2,**3**],
              [4,**5**,6],
              [**7**,8,**9**]]
Output: 25
**Explanation: **Diagonals sum: 1 + 5 + 9 + 3 + 7 = 25
Notice that element mat[1][1] = 5 is counted only once.
```
<br />**Example 2:**<br />
```
Input: mat = [[**1**,1,1,**1**],
              [1,**1**,**1**,1],
              [1,**1**,**1**,1],
              [**1**,1,1,**1**]]
Output: 8
```
<br />**Example 3:**<br />
```
Input: mat = [[**5**]]
Output: 5
```
<br /> <br />
<br />**Constraints:**<br />

* `n == mat.length == mat[i].length`

* `1 <;= n <;= 100`

* `1 <;= mat[i][j] <;= 100`