# 933. Number of Recent Calls

<br />You have a `RecentCounter` class which counts the number of recent requests within a certain time frame.<br />
<br />Implement the `RecentCounter` class:<br />

* `RecentCounter()` Initializes the counter with zero recent requests.

* `int ping(int t)` Adds a new request at time `t`, where `t` represents some time in milliseconds, and returns the number of requests that has happened in the past `3000` milliseconds (including the new request). Specifically, return the number of requests that have happened in the inclusive range `[t - 3000, t]`.


<br />It is **guaranteed** that every call to `ping` uses a strictly larger value of `t` than the previous call.<br />
<br /> <br />
<br />**Example 1:**<br />
```**Input**
["RecentCounter", "ping", "ping", "ping", "ping"]
[[], [1], [100], [3001], [3002]]
**Output**
[null, 1, 2, 3, 3]

**Explanation**
RecentCounter recentCounter = new RecentCounter();
recentCounter.ping(1);     // requests = [<u>1</u>], range is [-2999,1], return 1
recentCounter.ping(100);   // requests = [<u>1</u>, <u>100</u>], range is [-2900,100], return 2
recentCounter.ping(3001);  // requests = [<u>1</u>, <u>100</u>, <u>3001</u>], range is [1,3001], return 3
recentCounter.ping(3002);  // requests = [1, <u>100</u>, <u>3001</u>, <u>3002</u>], range is [2,3002], return 3
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= t <;= 10<sup>9</sup>`

* Each test case will call `ping` with **strictly increasing** values of `t`.

* At most `10<sup>4</sup>` calls will be made to `ping`.