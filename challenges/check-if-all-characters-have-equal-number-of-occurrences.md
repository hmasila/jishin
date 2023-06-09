# 1941. Check if All Characters Have Equal Number of Occurrences

<br />Given a string `s`, return `true`<em> if </em>`s`<em> is a **good** string, or </em>`false`<em> otherwise</em>.<br />
<br />A string `s` is **good** if **all** the characters that appear in `s` have the **same** number of occurrences (i.e., the same frequency).<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abacbc"
Output: true
Explanation: The characters that appear in s are 'a', 'b', and 'c'. All characters occur 2 times in s.
```
<br />**Example 2:**<br />
```
Input: s = "aaabb"
Output: false
Explanation: The characters that appear in s are 'a' and 'b'.
'a' occurs 3 times while 'b' occurs 2 times, which is not the same number of times.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 1000`

* `s` consists of lowercase English letters.