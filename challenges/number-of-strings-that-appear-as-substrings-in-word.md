# 1967. Number of Strings That Appear as Substrings in Word

<br />Given an array of strings `patterns` and a string `word`, return <em>the **number** of strings in </em>`patterns`<em> that exist as a **substring** in </em>`word`.<br />
<br />A **substring** is a contiguous sequence of characters within a string.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: patterns = ["a","abc","bc","d"], word = "abc"
Output: 3
Explanation:
- "a" appears as a substring in "<u>a</u>bc".
- "abc" appears as a substring in "<u>abc</u>".
- "bc" appears as a substring in "a<u>bc</u>".
- "d" does not appear as a substring in "abc".
3 of the strings in patterns appear as a substring in word.
```
<br />**Example 2:**<br />
```
Input: patterns = ["a","b","c"], word = "aaaaabbbbb"
Output: 2
Explanation:
- "a" appears as a substring in "a<u>a</u>aaabbbbb".
- "b" appears as a substring in "aaaaabbbb<u>b</u>".
- "c" does not appear as a substring in "aaaaabbbbb".
2 of the strings in patterns appear as a substring in word.
```
<br />**Example 3:**<br />
```
Input: patterns = ["a","a","a"], word = "ab"
Output: 3
Explanation: Each of the patterns appears as a substring in word "<u>a</u>b".
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= patterns.length <;= 100`

* `1 <;= patterns[i].length <;= 100`

* `1 <;= word.length <;= 100`

* `patterns[i]` and `word` consist of lowercase English letters.