# 401. Binary Watch

<br />A binary watch has 4 LEDs on the top to represent the hours (0-11), and 6 LEDs on the bottom to represent the minutes (0-59). Each LED represents a zero or one, with the least significant bit on the right.<br />

* For example, the below binary watch reads `"4:51"`.


<br /><img alt="" src="https://assets.leetcode.com/uploads/2021/04/08/binarywatch.jpg" style="width:500px;height:500px"/><br />
<br />Given an integer `turnedOn` which represents the number of LEDs that are currently on (ignoring the PM), return <em>all possible times the watch could represent</em>. You may return the answer in **any order**.<br />
<br />The hour must not contain a leading zero.<br />

* For example, `"01:00"` is not valid. It should be `"1:00"`.


<br />The minute must be consist of two digits and may contain a leading zero.<br />

* For example, `"10:2"` is not valid. It should be `"10:02"`.


<br /> <br />
<br />**Example 1:**<br />
```
Input: turnedOn = 1
Output: ["0:01","0:02","0:04","0:08","0:16","0:32","1:00","2:00","4:00","8:00"]
```<br />**Example 2:**<br />
```
Input: turnedOn = 9
Output: []
```
<br /> <br />
<br />**Constraints:**<br />

* `0 <;= turnedOn <;= 10`