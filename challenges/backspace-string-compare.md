# 844. Backspace String Compare

<br />Given two strings `s` and `t`, return `true` <em>if they are equal when both are typed into empty text editors</em>. `'#'` means a backspace character.<br />
<br />Note that after backspacing an empty text, the text will continue empty.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "ab#c", t = "ad#c"
Output: true
Explanation: Both s and t become "ac".
```
<br />**Example 2:**<br />
```
Input: s = "ab##", t = "c#d#"
Output: true
Explanation: Both s and t become "".
```
<br />**Example 3:**<br />
```
Input: s = "a#c", t = "b"
Output: false
Explanation: s becomes "c" while t becomes "b".
```
<br /> <br />
<br />**Constraints:**<br />

* `<span>1 <;= s.length, t.length <;= 200</span>`

* <span>`s` and `t` only contain lowercase letters and `'#'` characters.</span>


<br /> <br />
<br />**Follow up:** Can you solve it in `O(n)` time and `O(1)` space?<br />