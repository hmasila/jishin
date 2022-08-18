# 1598. Crawler Log Folder

<br />The Leetcode file system keeps a log each time some user performs a <em>change folder</em> operation.<br />
<br />The operations are described below:<br />

* `"../"` : Move to the parent folder of the current folder. (If you are already in the main folder, **remain in the same folder**).

* `"./"` : Remain in the same folder.

* `"x/"` : Move to the child folder named `x` (This folder is **guaranteed to always exist**).


<br />You are given a list of strings `logs` where `logs[i]` is the operation performed by the user at the `i<sup>th</sup>` step.<br />
<br />The file system starts in the main folder, then the operations in `logs` are performed.<br />
<br />Return <em>the minimum number of operations needed to go back to the main folder after the change folder operations.</em><br />
<br /> <br />
<br />**Example 1:**<br />
<br /><img alt="" src="https://assets.leetcode.com/uploads/2020/09/09/sample_11_1957.png" style="width:775px;height:151px"/><br />
```
Input: logs = ["d1/","d2/","../","d21/","./"]
Output: 2
**Explanation: **Use this change folder operation "../" 2 times and go back to the main folder.
```
<br />**Example 2:**<br />
<br /><img alt="" src="https://assets.leetcode.com/uploads/2020/09/09/sample_22_1957.png" style="width:600px;height:270px"/><br />
```
Input: logs = ["d1/","d2/","./","d3/","../","d31/"]
Output: 3
```
<br />**Example 3:**<br />
```
Input: logs = ["d1/","../","../","../"]
Output: 0
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= logs.length <;= 10<sup>3</sup>`

* `2 <;= logs[i].length <;= 10`

* `logs[i]` contains lowercase English letters, digits, `'.'`, and `'/'`.

* `logs[i]` follows the format described in the statement.

* Folder names consist of lowercase English letters and digits.