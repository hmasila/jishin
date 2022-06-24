# 1408. String Matching in an Array

<br />Given an array of string `words`, return <em>all strings in </em>`words`<em> that is a **substring** of another word</em>. You can return the answer in **any order**.<br />
<br />A **substring** is a contiguous sequence of characters within a string<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: words = ["mass","as","hero","superhero"]
Output: ["as","hero"]
Explanation: "as" is substring of "mass" and "hero" is substring of "superhero".
["hero","as"] is also a valid answer.
```
<br />**Example 2:**<br />
```
Input: words = ["leetcode","et","code"]
Output: ["et","code"]
Explanation: "et", "code" are substring of "leetcode".
```
<br />**Example 3:**<br />
```
Input: words = ["blue","green","bu"]
Output: []
Explanation: No string of words is substring of another string.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= words.length <;= 100`

* `1 <;= words[i].length <;= 30`

* `words[i]` contains only lowercase English letters.

* All the strings of `words` are **unique**.