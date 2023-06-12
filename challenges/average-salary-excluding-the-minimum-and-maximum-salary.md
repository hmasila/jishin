# 1491. Average Salary Excluding the Minimum and Maximum Salary

<br />You are given an array of **unique** integers `salary` where `salary[i]` is the salary of the `i<sup>th</sup>` employee.<br />
<br />Return <em>the average salary of employees excluding the minimum and maximum salary</em>. Answers within `10<sup>-5</sup>` of the actual answer will be accepted.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: salary = [4000,3000,1000,2000]
Output: 2500.00000
Explanation: Minimum salary and maximum salary are 1000 and 4000 respectively.
Average salary excluding minimum and maximum salary is (2000+3000) / 2 = 2500
```
<br />**Example 2:**<br />
```
Input: salary = [1000,2000,3000]
Output: 2000.00000
Explanation: Minimum salary and maximum salary are 1000 and 3000 respectively.
Average salary excluding minimum and maximum salary is (2000) / 1 = 2000
```
<br /> <br />
<br />**Constraints:**<br />

* `3 <;= salary.length <;= 100`

* `1000 <;= salary[i] <;= 10<sup>6</sup>`

* All the integers of `salary` are **unique**.