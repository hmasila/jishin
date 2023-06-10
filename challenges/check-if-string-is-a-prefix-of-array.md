# 1961. Check If String Is a Prefix of Array

<br />Given a string `s` and an array of strings `words`, determine whether `s` is a **prefix string** of `words`.<br />
<br />A string `s` is a **prefix string** of `words` if `s` can be made by concatenating the first `k` strings in `words` for some **positive** `k` no larger than `words.length`.<br />
<br />Return `true`<em> if </em>`s`<em> is a **prefix string** of </em>`words`<em>, or </em>`false`<em> otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "iloveleetcode", words = ["i","love","leetcode","apples"]
Output: true
Explanation:
s can be made by concatenating "i", "love", and "leetcode" together.
```
<br />**Example 2:**<br />
```
Input: s = "iloveleetcode", words = ["apples","i","love","leetcode"]
Output: false
Explanation:
It is impossible to make s using a prefix of arr.```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= words.length <;= 100`

* `1 <;= words[i].length <;= 20`

* `1 <;= s.length <;= 1000`

* `words[i]` and `s` consist of only lowercase English letters.