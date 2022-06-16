# 1496. Path Crossing

<br />Given a string `path`, where `path[i] = 'N'`, `'S'`, `'E'` or `'W'`, each representing moving one unit north, south, east, or west, respectively. You start at the origin `(0, 0)` on a 2D plane and walk on the path specified by `path`.<br />
<br />Return `true` <em>if the path crosses itself at any point, that is, if at any time you are on a location you have previously visited</em>. Return `false` otherwise.<br />
<br /> <br />
<br />**Example 1:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/06/10/screen-shot-2020-06-10-at-123929-pm.png" style="width:400px;height:358px"/>
```
Input: path = "NES"
Output: false 
Explanation: Notice that the path doesn't cross any point more than once.
```
<br />**Example 2:**<br />
<img alt="" src="https://assets.leetcode.com/uploads/2020/06/10/screen-shot-2020-06-10-at-123843-pm.png" style="width:400px;height:339px"/>
```
Input: path = "NESWW"
Output: true
Explanation: Notice that the path visits the origin twice.```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= path.length <;= 10<sup>4</sup>`

* `path[i]` is either `'N'`, `'S'`, `'E'`, or `'W'`.