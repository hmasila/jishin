# 1869. Longer Contiguous Segments of Ones than Zeros

<br />Given a binary string `s`, return `true`<em> if the **longest** contiguous segment of </em>`1`'<em>s is **strictly longer** than the **longest** contiguous segment of </em>`0`'<em>s in </em>`s`, or return `false`<em> otherwise</em>.<br />

* For example, in `s = "<u>11</u>01<u>000</u>10"` the longest continuous segment of `1`s has length `2`, and the longest continuous segment of `0`s has length `3`.


<br />Note that if there are no `0`'s, then the longest continuous segment of `0`'s is considered to have a length `0`. The same applies if there is no `1`'s.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "1101"
Output: true
Explanation:
The longest contiguous segment of 1s has length 2: "<u>11</u>01"
The longest contiguous segment of 0s has length 1: "11<u>0</u>1"
The segment of 1s is longer, so return true.
```
<br />**Example 2:**<br />
```
Input: s = "111000"
Output: false
Explanation:
The longest contiguous segment of 1s has length 3: "<u>111</u>000"
The longest contiguous segment of 0s has length 3: "111<u>000</u>"
The segment of 1s is not longer, so return false.
```
<br />**Example 3:**<br />
```
Input: s = "110100010"
Output: false
Explanation:
The longest contiguous segment of 1s has length 2: "<u>11</u>0100010"
The longest contiguous segment of 0s has length 3: "1101<u>000</u>10"
The segment of 1s is not longer, so return false.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= s.length <;= 100`

* `s[i]` is either `'0'` or `'1'`.