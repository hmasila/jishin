# 821. Shortest Distance to a Character

<br />Given a string `s` and a character `c` that occurs in `s`, return <em>an array of integers </em>`answer`<em> where </em>`answer.length == s.length`<em> and </em>`answer[i]`<em> is the **distance** from index </em>`i`<em> to the **closest** occurrence of character </em>`c`<em> in </em>`s`.<br />
<br />The **distance** between two indices `i` and `j` is `abs(i - j)`, where `abs` is the absolute value function.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "loveleetcode", c = "e"
Output: [3,2,1,0,1,0,0,1,2,2,1,0]
Explanation: The character 'e' appears at indices 3, 5, 6, and 11 (0-indexed).
The closest occurrence of 'e' for index 0 is at index 3, so the distance is abs(0 - 3) = 3.
The closest occurrence of 'e' for index 1 is at index 3, so the distance is abs(1 - 3) = 2.
For index 4, there is a tie between the 'e' at index 3 and the 'e' at index 5, but the distance is still the same: abs(4 - 3) == abs(4 - 5) = 1.
The closest occurrence of 'e' for index 8 is at index 6, so the distance is abs(8 - 6) = 2.
```
<br />**Example 2:**<br />
```
Input: s = "aaab", c = "b"
Output: [3,2,1,0]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 10<sup>4</sup>`

* `s[i]` and `c` are lowercase English letters.

* It is guaranteed that `c` occurs at least once in `s`.