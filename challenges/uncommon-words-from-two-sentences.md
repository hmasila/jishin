# 884. Uncommon Words from Two Sentences

<br />A **sentence** is a string of single-space separated words where each word consists only of lowercase letters.<br />
<br />A word is **uncommon** if it appears exactly once in one of the sentences, and **does not appear** in the other sentence.<br />
<br />Given two **sentences** `s1` and `s2`, return <em>a list of all the **uncommon words**</em>. You may return the answer in **any order**.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s1 = "this apple is sweet", s2 = "this apple is sour"
Output: ["sweet","sour"]
```<br />**Example 2:**<br />
```
Input: s1 = "apple apple", s2 = "banana"
Output: ["banana"]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s1.length, s2.length <;= 200`

* `s1` and `s2` consist of lowercase English letters and spaces.

* `s1` and `s2` do not have leading or trailing spaces.

* All the words in `s1` and `s2` are separated by a single space.