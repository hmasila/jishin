# 1812. Determine Color of a Chessboard Square

<br />You are given `coordinates`, a string that represents the coordinates of a square of the chessboard. Below is a chessboard for your reference.<br />
<br /><img alt="" src="https://assets.leetcode.com/uploads/2021/02/19/screenshot-2021-02-20-at-22159-pm.png" style="width:400px;height:396px"/><br />
<br />Return `true`<em> if the square is white, and </em>`false`<em> if the square is black</em>.<br />
<br />The coordinate will always represent a valid chessboard square. The coordinate will always have the letter first, and the number second.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: coordinates = "a1"
Output: false
Explanation: From the chessboard above, the square with coordinates "a1" is black, so return false.
```
<br />**Example 2:**<br />
```
Input: coordinates = "h3"
Output: true
Explanation: From the chessboard above, the square with coordinates "h3" is white, so return true.
```
<br />**Example 3:**<br />
```
Input: coordinates = "c7"
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `coordinates.length == 2`

* `'a' <;= coordinates[0] <;= 'h'`

* `'1' <;= coordinates[1] <;= '8'`