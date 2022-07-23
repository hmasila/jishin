# 1763. Longest Nice Substring

<br />A string `s` is **nice** if, for every letter of the alphabet that `s` contains, it appears **both** in uppercase and lowercase. For example, `"abABB"` is nice because `'A'` and `'a'` appear, and `'B'` and `'b'` appear. However, `"abA"` is not because `'b'` appears, but `'B'` does not.<br />
<br />Given a string `s`, return <em>the longest **substring** of `s` that is **nice**. If there are multiple, return the substring of the **earliest** occurrence. If there are none, return an empty string</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "YazaAay"
Output: "aAa"
**Explanation: **"aAa" is a nice string because 'A/a' is the only letter of the alphabet in s, and both 'A' and 'a' appear.
"aAa" is the longest nice substring.
```
<br />**Example 2:**<br />
```
Input: s = "Bb"
Output: "Bb"
Explanation: "Bb" is a nice string because both 'B' and 'b' appear. The whole string is a substring.
```
<br />**Example 3:**<br />
```
Input: s = "c"
Output: ""
Explanation: There are no nice substrings.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 100`

* `s` consists of uppercase and lowercase English letters.