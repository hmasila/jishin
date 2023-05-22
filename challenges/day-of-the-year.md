# 1154. Day of the Year

<br />Given a string `date` representing a <a href="https://en.wikipedia.org/wiki/Gregorian_calendar" target="_blank">Gregorian calendar</a> date formatted as `YYYY-MM-DD`, return <em>the day number of the year</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: date = "2019-01-09"
Output: 9
Explanation: Given date is the 9th day of the year in 2019.
```
<br />**Example 2:**<br />
```
Input: date = "2019-02-10"
Output: 41
```
<br /> <br />
<br />**Constraints:**<br />

* `date.length == 10`

* `date[4] == date[7] == '-'`, and all other `date[i]`'s are digits

* `date` represents a calendar date between Jan 1<sup>st</sup>, 1900 and Dec 31<sup>th</sup>, 2019.