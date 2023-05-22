# 925. Long Pressed Name

<br />Your friend is typing his `name` into a keyboard. Sometimes, when typing a character `c`, the key might get <em>long pressed</em>, and the character will be typed 1 or more times.<br />
<br />You examine the `typed` characters of the keyboard. Return `True` if it is possible that it was your friends name, with some characters (possibly none) being long pressed.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: name = "alex", typed = "aaleex"
Output: true
**Explanation: **'a' and 'e' in 'alex' were long pressed.
```
<br />**Example 2:**<br />
```
Input: name = "saeed", typed = "ssaaedd"
Output: false
**Explanation: **'e' must have been pressed twice, but it was not in the typed output.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= name.length, typed.length <;= 1000`

* `name` and `typed` consist of only lowercase English letters.