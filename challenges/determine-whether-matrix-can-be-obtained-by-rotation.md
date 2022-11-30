# 1886. Determine Whether Matrix Can Be Obtained By Rotation

<br />Given two `n x n` binary matrices `mat` and `target`, return `true`<em> if it is possible to make </em>`mat`<em> equal to </em>`target`<em> by **rotating** </em>`mat`<em> in **90-degree increments**, or </em>`false`<em> otherwise.</em><br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/05/20/grid3.png" style="width:301px;height:121px"/>
```
Input: mat = [[0,1],[1,0]], target = [[1,0],[0,1]]
Output: true
**Explanation: **We can rotate mat 90 degrees clockwise to make mat equal target.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/05/20/grid4.png" style="width:301px;height:121px"/>
```
Input: mat = [[0,1],[1,1]], target = [[1,0],[0,1]]
Output: false
Explanation: It is impossible to make mat equal to target by rotating mat.
```
<br />**Example 3:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/05/26/grid4.png" style="width:661px;height:184px"/>
```
Input: mat = [[0,0,0],[0,1,0],[1,1,1]], target = [[1,1,1],[0,1,0],[0,0,0]]
Output: true
**Explanation: **We can rotate mat 90 degrees clockwise two times to make mat equal target.
```
<br /> <br />
<br />**Constraints:**<br />

* `n == mat.length == target.length`

* `n == mat[i].length == target[i].length`

* `1 <;= n <;= 10`

* `mat[i][j]` and `target[i][j]` are either `0` or `1`.