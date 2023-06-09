# 1974. Minimum Time to Type Word Using Special Typewriter

<br />There is a special typewriter with lowercase English letters `'a'` to `'z'` arranged in a **circle** with a **pointer**. A character can **only** be typed if the pointer is pointing to that character. The pointer is **initially** pointing to the character `'a'`.<br />
<img alt="" src="https://assets.leetcode.com/uploads/2021/07/31/chart.jpg" style="width:530px;height:410px"/>
<br />Each second, you may perform one of the following operations:<br />

* Move the pointer one character **counterclockwise** or **clockwise**.

* Type the character the pointer is **currently** on.


<br />Given a string `word`, return the** minimum** number of seconds to type out the characters in `word`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: word = "abc"
Output: 5
<strong>Explanation: 
</strong>The characters are printed as follows:
- Type the character 'a' in 1 second since the pointer is initially on 'a'.
- Move the pointer clockwise to 'b' in 1 second.
- Type the character 'b' in 1 second.
- Move the pointer clockwise to 'c' in 1 second.
- Type the character 'c' in 1 second.
```
<br />**Example 2:**<br />
```
Input: word = "bza"
Output: 7
<strong>Explanation:
</strong>The characters are printed as follows:
- Move the pointer clockwise to 'b' in 1 second.
- Type the character 'b' in 1 second.
- Move the pointer counterclockwise to 'z' in 2 seconds.
- Type the character 'z' in 1 second.
- Move the pointer clockwise to 'a' in 1 second.
- Type the character 'a' in 1 second.
```
<br />**Example 3:**<br />
```
Input: word = "zjpc"
Output: 34
Explanation:
The characters are printed as follows:
- Move the pointer counterclockwise to 'z' in 1 second.
- Type the character 'z' in 1 second.
- Move the pointer clockwise to 'j' in 10 seconds.
- Type the character 'j' in 1 second.
- Move the pointer clockwise to 'p' in 6 seconds.
- Type the character 'p' in 1 second.
- Move the pointer counterclockwise to 'c' in 13 seconds.
- Type the character 'c' in 1 second.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= word.length <;= 100`

* `word` consists of lowercase English letters.