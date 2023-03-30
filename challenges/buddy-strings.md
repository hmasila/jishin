# 859. Buddy Strings

<br />Given two strings `s` and `goal`, return `true`<em> if you can swap two letters in </em>`s`<em> so the result is equal to </em>`goal`<em>, otherwise, return </em>`false`<em>.</em><br />
<br />Swapping letters is defined as taking two indices `i` and `j` (0-indexed) such that `i != j` and swapping the characters at `s[i]` and `s[j]`.<br />

* For example, swapping at indices `0` and `2` in `"abcd"` results in `"cbad"`.


<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "ab", goal = "ba"
Output: true
Explanation: You can swap s[0] = 'a' and s[1] = 'b' to get "ba", which is equal to goal.
```
<br />**Example 2:**<br />
```
Input: s = "ab", goal = "ab"
Output: false
Explanation: The only letters you can swap are s[0] = 'a' and s[1] = 'b', which results in "ba" != goal.
```
<br />**Example 3:**<br />
```
Input: s = "aa", goal = "aa"
Output: true
Explanation: You can swap s[0] = 'a' and s[1] = 'a' to get "aa", which is equal to goal.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length, goal.length <;= 2 * 10<sup>4</sup>`

* `s` and `goal` consist of lowercase letters.