# 1450. Number of Students Doing Homework at a Given Time

<br />Given two integer arrays `startTime` and `endTime` and given an integer `queryTime`.<br />
<br />The `ith` student started doing their homework at the time `startTime[i]` and finished it at time `endTime[i]`.<br />
<br />Return <em>the number of students</em> doing their homework at time `queryTime`. More formally, return the number of students where `queryTime` lays in the interval `[startTime[i], endTime[i]]` inclusive.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: startTime = [1,2,3], endTime = [3,2,7], queryTime = 4
Output: 1
Explanation: We have 3 students where:
The first student started doing homework at time 1 and finished at time 3 and wasn't doing anything at time 4.
The second student started doing homework at time 2 and finished at time 2 and also wasn't doing anything at time 4.
The third student started doing homework at time 3 and finished at time 7 and was the only student doing homework at time 4.
```
<br />**Example 2:**<br />
```
Input: startTime = [4], endTime = [4], queryTime = 4
Output: 1
Explanation: The only student was doing their homework at the queryTime.
```
<br /> <br />
<br />**Constraints:**<br />

* `startTime.length == endTime.length`

* `1 <;= startTime.length <;= 100`

* `1 <;= startTime[i] <;= endTime[i] <;= 1000`

* `1 <;= queryTime <;= 1000`