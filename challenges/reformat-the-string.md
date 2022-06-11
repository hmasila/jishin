# 1417. Reformat The String

<br />You are given an alphanumeric string `s`. (**Alphanumeric string** is a string consisting of lowercase English letters and digits).<br />
<br />You have to find a permutation of the string where no letter is followed by another letter and no digit is followed by another digit. That is, no two adjacent characters have the same type.<br />
<br />Return <em>the reformatted string</em> or return **an empty string** if it is impossible to reformat the string.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "a0b1c2"
Output: "0a1b2c"
Explanation: No two adjacent characters have the same type in "0a1b2c". "a0b1c2", "0a1b2c", "0c2a1b" are also valid permutations.
```
<br />**Example 2:**<br />
```
Input: s = "leetcode"
Output: ""
Explanation: "leetcode" has only characters so we cannot separate them by digits.
```
<br />**Example 3:**<br />
```
Input: s = "1229857369"
Output: ""
Explanation: "1229857369" has only digits so we cannot separate them by characters.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 500`

* `s` consists of only lowercase English letters and/or digits.