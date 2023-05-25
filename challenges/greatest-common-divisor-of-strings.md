# 1071. Greatest Common Divisor of Strings

<br />For two strings `s` and `t`, we say "`t` divides `s`" if and only if `s = t + ... + t` (i.e., `t` is concatenated with itself one or more times).<br />
<br />Given two strings `str1` and `str2`, return <em>the largest string </em>`x`<em> such that </em>`x`<em> divides both </em>`str1`<em> and </em>`str2`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: str1 = "ABCABC", str2 = "ABC"
Output: "ABC"
```
<br />**Example 2:**<br />
```
Input: str1 = "ABABAB", str2 = "ABAB"
Output: "AB"
```
<br />**Example 3:**<br />
```
Input: str1 = "LEET", str2 = "CODE"
Output: ""
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= str1.length, str2.length <;= 1000`

* `str1` and `str2` consist of English uppercase letters.