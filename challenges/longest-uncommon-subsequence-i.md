# 521. Longest Uncommon Subsequence I

<br />Given two strings `a` and `b`, return <em>the length of the **longest uncommon subsequence** between </em>`a` <em>and</em> `b`. If the longest uncommon subsequence does not exist, return `-1`.<br />
<br />An **uncommon subsequence** between two strings is a string that is a **subsequence of one but not the other**.<br />
<br />A **subsequence** of a string `s` is a string that can be obtained after deleting any number of characters from `s`.<br />

* For example, `"abc"` is a subsequence of `"aebdc"` because you can delete the underlined characters in `"a<u>e</u>b<u>d</u>c"` to get `"abc"`. Other subsequences of `"aebdc"` include `"aebdc"`, `"aeb"`, and `""` (empty string).


<br /> <br />
<br />**Example 1:**<br />
```
Input: a = "aba", b = "cdc"
Output: 3
Explanation: One longest uncommon subsequence is "aba" because "aba" is a subsequence of "aba" but not "cdc".
Note that "cdc" is also a longest uncommon subsequence.
```
<br />**Example 2:**<br />
```
Input: a = "aaa", b = "bbb"
Output: 3
Explanation: The longest uncommon subsequences are "aaa" and "bbb".
```
<br />**Example 3:**<br />
```
Input: a = "aaa", b = "aaa"
Output: -1
Explanation: Every subsequence of string a is also a subsequence of string b. Similarly, every subsequence of string b is also a subsequence of string a.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= a.length, b.length <;= 100`

* `a` and `b` consist of lower-case English letters.