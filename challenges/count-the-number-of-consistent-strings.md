# 1684. Count the Number of Consistent Strings

<br />You are given a string `allowed` consisting of **distinct** characters and an array of strings `words`. A string is **consistent **if all characters in the string appear in the string `allowed`.<br />
<br />Return<em> the number of **consistent** strings in the array </em>`words`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: allowed = "ab", words = ["ad","bd","aaab","baa","badab"]
Output: 2
Explanation: Strings "aaab" and "baa" are consistent since they only contain characters 'a' and 'b'.
```
<br />**Example 2:**<br />
```
Input: allowed = "abc", words = ["a","b","c","ab","ac","bc","abc"]
Output: 7
Explanation: All strings are consistent.
```
<br />**Example 3:**<br />
```
Input: allowed = "cad", words = ["cc","acd","b","ba","bac","bad","ac","d"]
Output: 4
Explanation: Strings "cc", "acd", "ac", and "d" are consistent.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= words.length <;= 10<sup>4</sup>`

* `1 <;= allowed.length <;=<sup> </sup>26`

* `1 <;= words[i].length <;= 10`

* The characters in `allowed` are **distinct**.

* `words[i]` and `allowed` contain only lowercase English letters.