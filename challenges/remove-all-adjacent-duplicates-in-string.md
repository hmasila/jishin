# 1047. Remove All Adjacent Duplicates In String

<br />You are given a string `s` consisting of lowercase English letters. A **duplicate removal** consists of choosing two **adjacent** and **equal** letters and removing them.<br />
<br />We repeatedly make **duplicate removals** on `s` until we no longer can.<br />
<br />Return <em>the final string after all such duplicate removals have been made</em>. It can be proven that the answer is **unique**.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abbaca"
Output: "ca"
Explanation: 
For example, in "abbaca" we could remove "bb" since the letters are adjacent and equal, and this is the only possible move.  The result of this move is that the string is "aaca", of which only "aa" is possible, so the final string is "ca".
```
<br />**Example 2:**<br />
```
Input: s = "azxxzy"
Output: "ay"
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 10<sup>5</sup>`

* `s` consists of lowercase English letters.