# 796. Rotate String

<br />Given two strings `s` and `goal`, return `true` <em>if and only if</em> `s` <em>can become</em> `goal` <em>after some number of **shifts** on</em> `s`.<br />
<br />A **shift** on `s` consists of moving the leftmost character of `s` to the rightmost position.<br />

* For example, if `s = "abcde"`, then it will be `"bcdea"` after one shift.


<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abcde", goal = "cdeab"
Output: true
```<br />**Example 2:**<br />
```
Input: s = "abcde", goal = "abced"
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length, goal.length <;= 100`

* `s` and `goal` consist of lowercase English letters.