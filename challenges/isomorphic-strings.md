# 205. Isomorphic Strings

<br />Given two strings `s` and `t`, <em>determine if they are isomorphic</em>.<br />
<br />Two strings `s` and `t` are isomorphic if the characters in `s` can be replaced to get `t`.<br />
<br />All occurrences of a character must be replaced with another character while preserving the order of characters. No two characters may map to the same character, but a character may map to itself.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "egg", t = "add"
Output: true
```<br />**Example 2:**<br />
```
Input: s = "foo", t = "bar"
Output: false
```<br />**Example 3:**<br />
```
Input: s = "paper", t = "title"
Output: true
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 5 * 10<sup>4</sup>`

* `t.length == s.length`

* `s` and `t` consist of any valid ascii character.