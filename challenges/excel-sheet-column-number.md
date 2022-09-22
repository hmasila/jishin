# 171. Excel Sheet Column Number

<br />Given a string `columnTitle` that represents the column title as appears in an Excel sheet, return <em>its corresponding column number</em>.<br />
<br />For example:<br />
```A ->; 1
B ->; 2
C ->; 3
...
Z ->; 26
AA ->; 27
AB ->; 28 
...
```
<br /> <br />
<br />**Example 1:**<br />
```
Input: columnTitle = "A"
Output: 1
```
<br />**Example 2:**<br />
```
Input: columnTitle = "AB"
Output: 28
```
<br />**Example 3:**<br />
```
Input: columnTitle = "ZY"
Output: 701
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= columnTitle.length <;= 7`

* `columnTitle` consists only of uppercase English letters.

* `columnTitle` is in the range `["A", "FXSHRXW"]`.