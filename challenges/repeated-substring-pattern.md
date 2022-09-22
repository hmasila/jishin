# 459. Repeated Substring Pattern

<br />Given a string `s`, check if it can be constructed by taking a substring of it and appending multiple copies of the substring together.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abab"
Output: true
Explanation: It is the substring "ab" twice.
```
<br />**Example 2:**<br />
```
Input: s = "aba"
Output: false
```
<br />**Example 3:**<br />
```
Input: s = "abcabcabcabc"
Output: true
Explanation: It is the substring "abc" four times or the substring "abcabc" twice.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 10<sup>4</sup>`

* `s` consists of lowercase English letters.