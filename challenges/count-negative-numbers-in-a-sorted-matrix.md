# 1351. Count Negative Numbers in a Sorted Matrix

<br />Given a `m x n` matrix `grid` which is sorted in non-increasing order both row-wise and column-wise, return <em>the number of **negative** numbers in</em> `grid`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: grid = [[4,3,2,-1],[3,2,1,-1],[1,1,-1,-2],[-1,-1,-2,-3]]
Output: 8
Explanation: There are 8 negatives number in the matrix.
```
<br />**Example 2:**<br />
```
Input: grid = [[3,2],[1,0]]
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* `m == grid.length`

* `n == grid[i].length`

* `1 <;= m, n <;= 100`

* `-100 <;= grid[i][j] <;= 100`


<br /> <br />
**Follow up:** Could you find an `O(n + m)` solution?