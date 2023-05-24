# 1030. Matrix Cells in Distance Order

<br />You are given four integers `row`, `cols`, `rCenter`, and `cCenter`. There is a `rows x cols` matrix and you are on the cell with the coordinates `(rCenter, cCenter)`.<br />
<br />Return <em>the coordinates of all cells in the matrix, sorted by their **distance** from </em>`(rCenter, cCenter)`<em> from the smallest distance to the largest distance</em>. You may return the answer in **any order** that satisfies this condition.<br />
<br />The **distance** between two cells `(r<sub>1</sub>, c<sub>1</sub>)` and `(r<sub>2</sub>, c<sub>2</sub>)` is `|r<sub>1</sub> - r<sub>2</sub>| + |c<sub>1</sub> - c<sub>2</sub>|`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: rows = 1, cols = 2, rCenter = 0, cCenter = 0
Output: [[0,0],[0,1]]
Explanation: The distances from (0, 0) to other cells are: [0,1]
```
<br />**Example 2:**<br />
```
Input: rows = 2, cols = 2, rCenter = 0, cCenter = 1
Output: [[0,1],[0,0],[1,1],[1,0]]
Explanation: The distances from (0, 1) to other cells are: [0,1,1,2]
The answer [[0,1],[1,1],[0,0],[1,0]] would also be accepted as correct.
```
<br />**Example 3:**<br />
```
Input: rows = 2, cols = 3, rCenter = 1, cCenter = 2
Output: [[1,2],[0,2],[1,1],[0,1],[1,0],[0,0]]
Explanation: The distances from (1, 2) to other cells are: [0,1,1,2,2,3]
There are other answers that would also be accepted as correct, such as [[1,2],[1,1],[0,2],[1,0],[0,1],[0,0]].
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= rows, cols <;= 100`

* `0 <;= rCenter <; rows`

* `0 <;= cCenter <; cols`