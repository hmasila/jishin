# 1897. Redistribute Characters to Make All Strings Equal

<br />You are given an array of strings `words` (**0-indexed**).<br />
<br />In one operation, pick two **distinct** indices `i` and `j`, where `words[i]` is a non-empty string, and move **any** character from `words[i]` to **any** position in `words[j]`.<br />
<br />Return `true` <em>if you can make** every** string in </em>`words`<em> **equal **using **any** number of operations</em>,<em> and </em>`false` <em>otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: words = ["abc","aabc","bc"]
Output: true
Explanation: Move the first 'a' in <code>words[1] to the front of words[2],
to make </code>`words[1]` = "abc" and words[2] = "abc".
All the strings are now equal to "abc", so return `true`.
```
<br />**Example 2:**<br />
```
Input: words = ["ab","a"]
Output: false
Explanation: It is impossible to make all the strings equal using the operation.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= words.length <;= 100`

* `1 <;= words[i].length <;= 100`

* `words[i]` consists of lowercase English letters.