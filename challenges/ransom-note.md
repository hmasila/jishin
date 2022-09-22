# 383. Ransom Note

<br />Given two strings `ransomNote` and `magazine`, return `true`<em> if </em>`ransomNote`<em> can be constructed by using the letters from </em>`magazine`<em> and </em>`false`<em> otherwise</em>.<br />
<br />Each letter in `magazine` can only be used once in `ransomNote`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: ransomNote = "a", magazine = "b"
Output: false
```<br />**Example 2:**<br />
```
Input: ransomNote = "aa", magazine = "ab"
Output: false
```<br />**Example 3:**<br />
```
Input: ransomNote = "aa", magazine = "aab"
Output: true
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= ransomNote.length, magazine.length <;= 10<sup>5</sup>`

* `ransomNote` and `magazine` consist of lowercase English letters.