# 1668. Maximum Repeating Substring

<br />For a string `sequence`, a string `word` is **`k`-repeating** if `word` concatenated `k` times is a substring of `sequence`. The `word`'s **maximum `k`-repeating value** is the highest value `k` where `word` is `k`-repeating in `sequence`. If `word` is not a substring of `sequence`, `word`'s maximum `k`-repeating value is `0`.<br />
<br />Given strings `sequence` and `word`, return <em>the **maximum `k`-repeating value** of `word` in `sequence`</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: sequence = "ababc", word = "ab"
Output: 2
**Explanation: **"abab" is a substring in "<u>abab</u>c".
```
<br />**Example 2:**<br />
```
Input: sequence = "ababc", word = "ba"
Output: 1
**Explanation: **"ba" is a substring in "a<u>ba</u>bc". "baba" is not a substring in "ababc".
```
<br />**Example 3:**<br />
```
Input: sequence = "ababc", word = "ac"
Output: 0
**Explanation: **"ac" is not a substring in "ababc". 
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= sequence.length <;= 100`

* `1 <;= word.length <;= 100`

* `sequence` and `word` contains only lowercase English letters.