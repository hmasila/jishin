# 1957. Delete Characters to Make Fancy String

<br />A **fancy string** is a string where no **three** **consecutive** characters are equal.<br />
<br />Given a string `s`, delete the **minimum** possible number of characters from `s` to make it **fancy**.<br />
<br />Return <em>the final string after the deletion</em>. It can be shown that the answer will always be **unique**.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "le<u>e</u>etcode"
Output: "leetcode"
Explanation:
Remove an 'e' from the first group of 'e's to create "leetcode".
No three consecutive characters are equal, so return "leetcode".
```
<br />**Example 2:**<br />
```
Input: s = "<u>a</u>aab<u>aa</u>aa"
Output: "aabaa"
Explanation:
Remove an 'a' from the first group of 'a's to create "aabaaaa".
Remove two 'a's from the second group of 'a's to create "aabaa".
No three consecutive characters are equal, so return "aabaa".
```
<br />**Example 3:**<br />
```
Input: s = "aab"
Output: "aab"
Explanation: No three consecutive characters are equal, so return "aab".
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 10<sup>5</sup>`

* `s` consists only of lowercase English letters.