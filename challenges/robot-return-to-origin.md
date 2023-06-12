# 657. Robot Return to Origin

<br />There is a robot starting at the position `(0, 0)`, the origin, on a 2D plane. Given a sequence of its moves, judge if this robot **ends up at **`(0, 0)` after it completes its moves.<br />
<br />You are given a string `moves` that represents the move sequence of the robot where `moves[i]` represents its `i<sup>th</sup>` move. Valid moves are `'R'` (right), `'L'` (left), `'U'` (up), and `'D'` (down).<br />
<br />Return `true`<em> if the robot returns to the origin after it finishes all of its moves, or </em>`false`<em> otherwise</em>.<br />
<br />**Note**: The way that the robot is "facing" is irrelevant. `'R'` will always make the robot move to the right once, `'L'` will always make it move left, etc. Also, assume that the magnitude of the robot's movement is the same for each move.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: moves = "UD"
Output: true
**Explanation**: The robot moves up once, and then down once. All moves have the same magnitude, so it ended up at the origin where it started. Therefore, we return true.
```
<br />**Example 2:**<br />
```
Input: moves = "LL"
Output: false
**Explanation**: The robot moves left twice. It ends up two "moves" to the left of the origin. We return false because it is not at the origin at the end of its moves.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= moves.length <;= 2 * 10<sup>4</sup>`

* `moves` only contains the characters `'U'`, `'D'`, `'L'` and `'R'`.