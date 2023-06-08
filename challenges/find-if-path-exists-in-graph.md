# 1971. Find if Path Exists in Graph

<br />There is a **bi-directional** graph with `n` vertices, where each vertex is labeled from `0` to `n - 1` (**inclusive**). The edges in the graph are represented as a 2D integer array `edges`, where each `edges[i] = [u<sub>i</sub>, v<sub>i</sub>]` denotes a bi-directional edge between vertex `u<sub>i</sub>` and vertex `v<sub>i</sub>`. Every vertex pair is connected by **at most one** edge, and no vertex has an edge to itself.<br />
<br />You want to determine if there is a **valid path** that exists from vertex `source` to vertex `destination`.<br />
<br />Given `edges` and the integers `n`, `source`, and `destination`, return `true`<em> if there is a **valid path** from </em>`source`<em> to </em>`destination`<em>, or </em>`false`<em> otherwise</em><em>.</em><br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/08/14/validpath-ex1.png" style="width:141px;height:121px"/>
```
Input: n = 3, edges = [[0,1],[1,2],[2,0]], source = 0, destination = 2
Output: true
Explanation: There are two paths from vertex 0 to vertex 2:
- 0 → 1 → 2
- 0 → 2
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/08/14/validpath-ex2.png" style="width:281px;height:141px"/>
```
Input: n = 6, edges = [[0,1],[0,2],[3,5],[5,4],[4,3]], source = 0, destination = 5
Output: false
Explanation: There is no path from vertex 0 to vertex 5.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 2 * 10<sup>5</sup>`

* `0 <;= edges.length <;= 2 * 10<sup>5</sup>`

* `edges[i].length == 2`

* `0 <;= u<sub>i</sub>, v<sub>i</sub> <;= n - 1`

* `u<sub>i</sub> != v<sub>i</sub>`

* `0 <;= source, destination <;= n - 1`

* There are no duplicate edges.

* There are no self edges.