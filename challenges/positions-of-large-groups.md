# 830. Positions of Large Groups

<br />In a string `<font face="monospace">s</font>` of lowercase letters, these letters form consecutive groups of the same character.<br />
<br />For example, a string like `s = "abbxxxxzyy"` has the groups `"a"`, `"bb"`, `"xxxx"`, `"z"`, and `"yy"`.<br />
<br />A group is identified by an interval `[start, end]`, where `start` and `end` denote the start and end indices (inclusive) of the group. In the above example, `"xxxx"` has the interval `[3,6]`.<br />
<br />A group is considered **large** if it has 3 or more characters.<br />
<br />Return <em>the intervals of every **large** group sorted in **increasing order by start index**</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "abbxxxxzzy"
Output: [[3,6]]
Explanation: `"xxxx" is the only `large group with start index 3 and end index 6.
```
<br />**Example 2:**<br />
```
Input: s = "abc"
Output: []
Explanation: We have groups "a", "b", and "c", none of which are large groups.
```
<br />**Example 3:**<br />
```
Input: s = "abcdddeeeeaabbbcd"
Output: [[3,5],[6,9],[12,14]]
Explanation: The large groups are "ddd", "eeee", and "bbb".
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 1000`

* `s` contains lowercase English letters only.