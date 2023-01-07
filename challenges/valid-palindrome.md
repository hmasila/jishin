# 125. Valid Palindrome

<br />A phrase is a **palindrome** if, after converting all uppercase letters into lowercase letters and removing all non-alphanumeric characters, it reads the same forward and backward. Alphanumeric characters include letters and numbers.<br />
<br />Given a string `s`, return `true`<em> if it is a **palindrome**, or </em>`false`<em> otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "A man, a plan, a canal: Panama"
Output: true
Explanation: "amanaplanacanalpanama" is a palindrome.
```
<br />**Example 2:**<br />
```
Input: s = "race a car"
Output: false
Explanation: "raceacar" is not a palindrome.
```
<br />**Example 3:**<br />
```
Input: s = " "
Output: true
Explanation: s is an empty string "" after removing non-alphanumeric characters.
Since an empty string reads the same forward and backward, it is a palindrome.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 2 * 10<sup>5</sup>`

* `s` consists only of printable ASCII characters.