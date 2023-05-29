# 1221. Split a String in Balanced Strings

<br />**Balanced** strings are those that have an equal quantity of `'L'` and `'R'` characters.<br />
<br />Given a **balanced** string `s`, split it into some number of substrings such that:<br />

* Each substring is balanced.


<br />Return <em>the **maximum** number of balanced strings you can obtain.</em><br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "RLRRLLRLRL"
Output: 4
Explanation: s can be split into "RL", "RRLL", "RL", "RL", each substring contains same number of 'L' and 'R'.
```
<br />**Example 2:**<br />
```
Input: s = "RLRRRLLRLL"
Output: 2
Explanation: s can be split into "RL", "RRRLLRLL", each substring contains same number of 'L' and 'R'.
Note that s cannot be split into "RL", "RR", "RL", "LR", "LL", because the 2<sup>nd</sup> and 5<sup>th</sup> substrings are not balanced.```
<br />**Example 3:**<br />
```
Input: s = "LLLLRRRR"
Output: 1
Explanation: s can be split into "LLLLRRRR".
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= s.length <;= 1000`

* `s[i]` is either `'L'` or `'R'`.

* `s` is a **balanced** string.