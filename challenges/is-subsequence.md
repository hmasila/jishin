# 392. Is Subsequence

<br />Given two strings `s` and `t`, return `true`<em> if </em>`s`<em> is a **subsequence** of </em>`t`<em>, or </em>`false`<em> otherwise</em>.<br />
<br />A **subsequence** of a string is a new string that is formed from the original string by deleting some (can be none) of the characters without disturbing the relative positions of the remaining characters. (i.e., `"ace"` is a subsequence of `"<u>a</u>b<u>c</u>d<u>e</u>"` while `"aec"` is not).<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abc", t = "ahbgdc"
Output: true
```<br />**Example 2:**<br />
```
Input: s = "axc", t = "ahbgdc"
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= s.length <;= 100`

* `0 <;= t.length <;= 10<sup>4</sup>`

* `s` and `t` consist only of lowercase English letters.


<br /> <br />
**Follow up:** Suppose there are lots of incoming `s`, say `s<sub>1</sub>, s<sub>2</sub>, ..., s<sub>k</sub>` where `k >;= 10<sup>9</sup>`, and you want to check one by one to see if `t` has its subsequence. In this scenario, how would you change your code?