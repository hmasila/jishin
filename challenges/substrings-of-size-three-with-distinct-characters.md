# 1876. Substrings of Size Three with Distinct Characters

<br />A string is **good** if there are no repeated characters.<br />
<br />Given a string `s`​​​​​, return <em>the number of **good substrings** of length **three **in </em>`s`​​​​​​.<br />
<br />Note that if there are multiple occurrences of the same substring, every occurrence should be counted.<br />
<br />A **substring** is a contiguous sequence of characters in a string.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "xyzzaz"
Output: 1
Explanation: There are 4 substrings of size 3: "xyz", "yzz", "zza", and "zaz". 
The only good substring of length 3 is "xyz".
```
<br />**Example 2:**<br />
```
Input: s = "aababcabc"
Output: 4
Explanation: There are 7 substrings of size 3: "aab", "aba", "bab", "abc", "bca", "cab", and "abc".
The good substrings are "abc", "bca", "cab", and "abc".
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 100`

* `s`​​​​​​ consists of lowercase English letters.