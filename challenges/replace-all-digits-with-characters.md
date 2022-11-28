# 1844. Replace All Digits with Characters

<br />You are given a **0-indexed** string `s` that has lowercase English letters in its **even** indices and digits in its **odd** indices.<br />
<br />There is a function `shift(c, x)`, where `c` is a character and `x` is a digit, that returns the `x<sup>th</sup>` character after `c`.<br />

* For example, `shift('a', 5) = 'f'` and `shift('x', 0) = 'x'`.


<br />For every **odd** index `i`, you want to replace the digit `s[i]` with `shift(s[i-1], s[i])`.<br />
<br />Return `s`<em> after replacing all digits. It is **guaranteed** that </em>`shift(s[i-1], s[i])`<em> will never exceed </em>`'z'`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "a1c1e1"
Output: "abcdef"
**Explanation: **The digits are replaced as follows:
- s[1] ->; shift('a',1) = 'b'
- s[3] ->; shift('c',1) = 'd'
- s[5] ->; shift('e',1) = 'f'```
<br />**Example 2:**<br />
```
Input: s = "a1b2c3d4e"
Output: "abbdcfdhe"
**Explanation: **The digits are replaced as follows:
- s[1] ->; shift('a',1) = 'b'
- s[3] ->; shift('b',2) = 'd'
- s[5] ->; shift('c',3) = 'f'
- s[7] ->; shift('d',4) = 'h'```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 100`

* `s` consists only of lowercase English letters and digits.

* `shift(s[i-1], s[i]) <;= 'z'` for all **odd** indices `i`.