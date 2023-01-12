# 744. Find Smallest Letter Greater Than Target

<br />You are given an array of characters `letters` that is sorted in **non-decreasing order**, and a character `target`. There are **at least two different** characters in `letters`.<br />
<br />Return <em>the smallest character in </em>`letters`<em> that is lexicographically greater than </em>`target`. If such a character does not exist, return the first character in `letters`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: letters = ["c","f","j"], target = "a"
Output: "c"
Explanation: The smallest character that is lexicographically greater than 'a' in letters is 'c'.
```
<br />**Example 2:**<br />
```
Input: letters = ["c","f","j"], target = "c"
Output: "f"
Explanation: The smallest character that is lexicographically greater than 'c' in letters is 'f'.
```
<br />**Example 3:**<br />
```
Input: letters = ["x","x","y","y"], target = "z"
Output: "x"
Explanation: There are no characters in letters that is lexicographically greater than 'z' so we return letters[0].
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= letters.length <;= 10<sup>4</sup>`

* `letters[i]` is a lowercase English letter.

* `letters` is sorted in **non-decreasing** order.

* `letters` contains at least two different characters.

* `target` is a lowercase English letter.