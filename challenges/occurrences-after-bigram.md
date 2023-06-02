# 1078. Occurrences After Bigram

<br />Given two strings `first` and `second`, consider occurrences in some text of the form `"first second third"`, where `second` comes immediately after `first`, and `third` comes immediately after `second`.<br />
<br />Return <em>an array of all the words</em> `third` <em>for each occurrence of</em> `"first second third"`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: text = "alice is a good girl she is a good student", first = "a", second = "good"
Output: ["girl","student"]
```<br />**Example 2:**<br />
```
Input: text = "we will we will rock you", first = "we", second = "will"
Output: ["we","rock"]
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= text.length <;= 1000`

* `text` consists of lowercase English letters and spaces.

* All the words in `text` a separated by **a single space**.

* `1 <;= first.length, second.length <;= 10`

* `first` and `second` consist of lowercase English letters.