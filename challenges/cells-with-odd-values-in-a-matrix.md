# 1252. Cells with Odd Values in a Matrix

<br />There is an `m x n` matrix that is initialized to all `0`'s. There is also a 2D array `indices` where each `indices[i] = [r<sub>i</sub>, c<sub>i</sub>]` represents a **0-indexed location** to perform some increment operations on the matrix.<br />
<br />For each location `indices[i]`, do **both** of the following:<br />
<ol>
* Increment **all** the cells on row `r<sub>i</sub>`.

* Increment **all** the cells on column `c<sub>i</sub>`.

</ol>
<br />Given `m`, `n`, and `indices`, return <em>the **number of odd-valued cells** in the matrix after applying the increment to all locations in </em>`indices`.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/10/30/e1.png" style="width:600px;height:118px"/>
```
Input: m = 2, n = 3, indices = [[0,1],[1,1]]
Output: 6
Explanation: Initial matrix = [[0,0,0],[0,0,0]].
After applying first increment it becomes [[1,2,1],[0,1,0]].
The final matrix is [[1,3,1],[1,3,1]], which contains 6 odd numbers.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2019/10/30/e2.png" style="width:600px;height:150px"/>
```
Input: m = 2, n = 2, indices = [[1,1],[0,0]]
Output: 0
Explanation: Final matrix = [[2,2],[2,2]]. There are no odd numbers in the final matrix.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= m, n <;= 50`

* `1 <;= indices.length <;= 100`

* `0 <;= r<sub>i</sub> <; m`

* `0 <;= c<sub>i</sub> <; n`


<br /> <br />
<br />**Follow up:** Could you solve this in `O(n + m + indices.length)` time with only `O(n + m)` extra space?<br />