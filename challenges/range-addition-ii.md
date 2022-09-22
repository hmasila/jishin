# 598. Range Addition II

<br />You are given an `m x n` matrix `M` initialized with all `0`'s and an array of operations `ops`, where `ops[i] = [a<sub>i</sub>, b<sub>i</sub>]` means `M[x][y]` should be incremented by one for all `0 <;= x <; a<sub>i</sub>` and `0 <;= y <; b<sub>i</sub>`.<br />
<br />Count and return <em>the number of maximum integers in the matrix after performing all the operations</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/10/02/ex1.jpg" style="width:750px;height:176px"/>
```
Input: m = 3, n = 3, ops = [[2,2],[3,3]]
Output: 4
Explanation: The maximum integer in M is 2, and there are four of it in M. So return 4.
```
<br />**Example 2:**<br />
```
Input: m = 3, n = 3, ops = [[2,2],[3,3],[3,3],[3,3],[2,2],[3,3],[3,3],[3,3],[2,2],[3,3],[3,3],[3,3]]
Output: 4
```
<br />**Example 3:**<br />
```
Input: m = 3, n = 3, ops = []
Output: 9
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= m, n <;= 4 * 10<sup>4</sup>`

* `0 <;= ops.length <;= 10<sup>4</sup>`

* `ops[i].length == 2`

* `1 <;= a<sub>i</sub> <;= m`

* `1 <;= b<sub>i</sub> <;= n`