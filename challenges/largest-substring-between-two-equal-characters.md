# 1624. Largest Substring Between Two Equal Characters

<br />Given a string `s`, return <em>the length of the longest substring between two equal characters, excluding the two characters.</em> If there is no such substring return `-1`.<br />
<br />A **substring** is a contiguous sequence of characters within a string.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "aa"
Output: 0
Explanation: The optimal substring here is an empty substring between the two `'a's`.```
<br />**Example 2:**<br />
```
Input: s = "abca"
Output: 2
Explanation: The optimal substring here is "bc".
```
<br />**Example 3:**<br />
```
Input: s = "cbzxy"
Output: -1
Explanation: There are no characters that appear twice in s.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 300`

* `s` contains only lowercase English letters.