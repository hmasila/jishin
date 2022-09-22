# 389. Find the Difference

<br />You are given two strings `s` and `t`.<br />
<br />String `t` is generated by random shuffling string `s` and then add one more letter at a random position.<br />
<br />Return the letter that was added to `t`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abcd", t = "abcde"
Output: "e"
Explanation: 'e' is the letter that was added.
```
<br />**Example 2:**<br />
```
Input: s = "", t = "y"
Output: "y"
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= s.length <;= 1000`

* `t.length == s.length + 1`

* `s` and `t` consist of lowercase English letters.