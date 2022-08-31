# 1736. Latest Time by Replacing Hidden Digits

<br />You are given a string `time` in the form of ` hh:mm`, where some of the digits in the string are hidden (represented by `?`).<br />
<br />The valid times are those inclusively between `00:00` and `23:59`.<br />
<br />Return <em>the latest valid time you can get from</em> `time`<em> by replacing the hidden</em> <em>digits</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: time = "2?:?0"
Output: "23:50"
Explanation: The latest hour beginning with the digit '2' is 23 and the latest minute ending with the digit '0' is 50.
```
<br />**Example 2:**<br />
```
Input: time = "0?:3?"
Output: "09:39"
```
<br />**Example 3:**<br />
```
Input: time = "1?:22"
Output: "19:22"
```
<br /> <br />
<br />**Constraints:**<br />

* `time` is in the format `hh:mm`.

* It is guaranteed that you can produce a valid time from the given string.