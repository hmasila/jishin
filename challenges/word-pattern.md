# 290. Word Pattern

<br />Given a `pattern` and a string `s`, find if `s` follows the same pattern.<br />
<br />Here <b>follow</b> means a full match, such that there is a bijection between a letter in `pattern` and a <b>non-empty</b> word in `s`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: pattern = "abba", s = "dog cat cat dog"
Output: true
```
<br />**Example 2:**<br />
```
Input: pattern = "abba", s = "dog cat cat fish"
Output: false
```
<br />**Example 3:**<br />
```
Input: pattern = "aaaa", s = "dog cat cat dog"
Output: false
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= pattern.length <;= 300`

* `pattern` contains only lower-case English letters.

* `1 <;= s.length <;= 3000`

* `s` contains only lowercase English letters and spaces `' '`.

* `s` **does not contain** any leading or trailing spaces.

* All the words in `s` are separated by a **single space**.