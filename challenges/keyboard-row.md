# 500. Keyboard Row

<br />Given an array of strings `words`, return <em>the words that can be typed using letters of the alphabet on only one row of American keyboard like the image below</em>.<br />
<br />In the **American keyboard**:<br />

* the first row consists of the characters `"qwertyuiop"`,

* the second row consists of the characters `"asdfghjkl"`, and

* the third row consists of the characters `"zxcvbnm"`.


<img alt="" src="https://assets.leetcode.com/uploads/2018/10/12/keyboard.png" style="width:800px;max-width:600px;height:267px"/>
<br /> <br />
<br />**Example 1:**<br />
```
Input: words = ["Hello","Alaska","Dad","Peace"]
Output: ["Alaska","Dad"]
```
<br />**Example 2:**<br />
```
Input: words = ["omk"]
Output: []
```
<br />**Example 3:**<br />
```
Input: words = ["adsdf","sfd"]
Output: ["adsdf","sfd"]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= words.length <;= 20`

* `1 <;= words[i].length <;= 100`

* `words[i]` consists of English letters (both lowercase and uppercase).