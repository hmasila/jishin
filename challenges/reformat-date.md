# 1507. Reformat Date

<br />Given a `date` string in the form `Day Month Year`, where:<br />

* `Day` is in the set `{"1st", "2nd", "3rd", "4th", ..., "30th", "31st"}`.

* `Month` is in the set `{"Jan", "Feb", "Mar", "Apr", "May", "Jun", "Jul", "Aug", "Sep", "Oct", "Nov", "Dec"}`.

* `Year` is in the range `[1900, 2100]`.


<br />Convert the date string to the format `YYYY-MM-DD`, where:<br />

* `YYYY` denotes the 4 digit year.

* `MM` denotes the 2 digit month.

* `DD` denotes the 2 digit day.


<br /> <br />
<br />**Example 1:**<br />
```
Input: date = "20th Oct 2052"
Output: "2052-10-20"
```
<br />**Example 2:**<br />
```
Input: date = "6th Jun 1933"
Output: "1933-06-06"
```
<br />**Example 3:**<br />
```
Input: date = "26th May 1960"
Output: "1960-05-26"
```
<br /> <br />
<br />**Constraints:**<br />

* The given dates are guaranteed to be valid, so no error handling is necessary.