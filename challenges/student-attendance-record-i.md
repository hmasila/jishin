# 551. Student Attendance Record I

<br />You are given a string `s` representing an attendance record for a student where each character signifies whether the student was absent, late, or present on that day. The record only contains the following three characters:<br />

* `'A'`: Absent.

* `'L'`: Late.

* `'P'`: Present.


<br />The student is eligible for an attendance award if they meet **both** of the following criteria:<br />

* The student was absent (`'A'`) for **strictly** fewer than 2 days **total**.

* The student was **never** late (`'L'`) for 3 or more **consecutive** days.


<br />Return `true`<em> if the student is eligible for an attendance award, or </em>`false`<em> otherwise</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "PPALLP"
Output: true
Explanation: The student has fewer than 2 absences and was never late 3 or more consecutive days.
```
<br />**Example 2:**<br />
```
Input: s = "PPALLL"
Output: false
Explanation: The student was late 3 consecutive days in the last 3 days, so is not eligible for the award.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 1000`

* `s[i]` is either `'A'`, `'L'`, or `'P'`.