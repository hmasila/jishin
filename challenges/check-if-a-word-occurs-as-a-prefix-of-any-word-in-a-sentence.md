# 1455. Check If a Word Occurs As a Prefix of Any Word in a Sentence

<br />Given a `sentence` that consists of some words separated by a **single space**, and a `searchWord`, check if `searchWord` is a prefix of any word in `sentence`.<br />
<br />Return <em>the index of the word in </em>`sentence`<em> (**1-indexed**) where </em>`searchWord`<em> is a prefix of this word</em>. If `searchWord` is a prefix of more than one word, return the index of the first word **(minimum index)**. If there is no such word return `-1`.<br />
<br />A **prefix** of a string `s` is any leading contiguous substring of `s`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: sentence = "i love eating burger", searchWord = "burg"
Output: 4
Explanation: "burg" is prefix of "burger" which is the 4th word in the sentence.
```
<br />**Example 2:**<br />
```
Input: sentence = "this problem is an easy problem", searchWord = "pro"
Output: 2
Explanation: "pro" is prefix of "problem" which is the 2nd and the 6th word in the sentence, but we return 2 as it's the minimal index.
```
<br />**Example 3:**<br />
```
Input: sentence = "i am tired", searchWord = "you"
Output: -1
Explanation: "you" is not a prefix of any word in the sentence.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= sentence.length <;= 100`

* `1 <;= searchWord.length <;= 10`

* `sentence` consists of lowercase English letters and spaces.

* `searchWord` consists of lowercase English letters.