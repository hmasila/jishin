# 1160. Find Words That Can Be Formed by Characters

<br />You are given an array of strings `words` and a string `chars`.<br />
<br />A string is **good** if it can be formed by characters from chars (each character can only be used once).<br />
<br />Return <em>the sum of lengths of all good strings in words</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: words = ["cat","bt","hat","tree"], chars = "atach"
Output: 6
Explanation: The strings that can be formed are "cat" and "hat" so the answer is 3 + 3 = 6.
```
<br />**Example 2:**<br />
```
Input: words = ["hello","world","leetcode"], chars = "welldonehoneyr"
Output: 10
Explanation: The strings that can be formed are "hello" and "world" so the answer is 5 + 5 = 10.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= words.length <;= 1000`

* `1 <;= words[i].length, chars.length <;= 100`

* `words[i]` and `chars` consist of lowercase English letters.