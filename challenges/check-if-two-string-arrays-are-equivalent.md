# 1662. Check If Two String Arrays are Equivalent

<br />Given two string arrays `word1` and `word2`, return<em> </em>`true`<em> if the two arrays **represent** the same string, and </em>`false`<em> otherwise.</em><br />
<br />A string is **represented** by an array if the array elements concatenated **in order** forms the string.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: word1 = ["ab", "c"], word2 = ["a", "bc"]
Output: true
Explanation:
word1 represents string "ab" + "c" ->; "abc"
word2 represents string "a" + "bc" ->; "abc"
The strings are the same, so return true.```
<br />**Example 2:**<br />
```
Input: word1 = ["a", "cb"], word2 = ["ab", "c"]
Output: false
```
<br />**Example 3:**<br />
```
Input: word1  = ["abc", "d", "defg"], word2 = ["abcddefg"]
Output: true
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= word1.length, word2.length <;= 10<sup>3</sup>`

* `1 <;= word1[i].length, word2[i].length <;= 10<sup>3</sup>`

* `1 <;= sum(word1[i].length), sum(word2[i].length) <;= 10<sup>3</sup>`

* `word1[i]` and `word2[i]` consist of lowercase letters.