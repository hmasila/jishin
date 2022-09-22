# 541. Reverse String II

<br />Given a string `s` and an integer `k`, reverse the first `k` characters for every `2k` characters counting from the start of the string.<br />
<br />If there are fewer than `k` characters left, reverse all of them. If there are less than `2k` but greater than or equal to `k` characters, then reverse the first `k` characters and leave the other as original.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abcdefg", k = 2
Output: "bacdfeg"
```<br />**Example 2:**<br />
```
Input: s = "abcd", k = 2
Output: "bacd"
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 10<sup>4</sup>`

* `s` consists of only lowercase English letters.

* `1 <;= k <;= 10<sup>4</sup>`