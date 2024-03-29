# 1791. Find Center of Star Graph

<br />There is an undirected **star** graph consisting of `n` nodes labeled from `1` to `n`. A star graph is a graph where there is one **center** node and **exactly** `n - 1` edges that connect the center node with every other node.<br />
<br />You are given a 2D integer array `edges` where each `edges[i] = [u<sub>i</sub>, v<sub>i</sub>]` indicates that there is an edge between the nodes `u<sub>i</sub>` and `v<sub>i</sub>`. Return the center of the given star graph.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/02/24/star_graph.png" style="width:331px;height:321px"/>
```
Input: edges = [[1,2],[2,3],[4,2]]
Output: 2
Explanation: As shown in the figure above, node 2 is connected to every other node, so 2 is the center.
```
<br />**Example 2:**<br />
```
Input: edges = [[1,2],[5,1],[1,3],[1,4]]
Output: 1
```
<br /> <br />
<br />**Constraints:**<br />

* `3 <;= n <;= 10<sup>5</sup>`

* `edges.length == n - 1`

* `edges[i].length == 2`

* `1 <;= u<sub>i,</sub> v<sub>i</sub> <;= n`

* `u<sub>i</sub> != v<sub>i</sub>`

* The given `edges` represent a valid star graph.