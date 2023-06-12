# 1704. Determine if String Halves Are Alike

<br />You are given a string `s` of even length. Split this string into two halves of equal lengths, and let `a` be the first half and `b` be the second half.<br />
<br />Two strings are **alike** if they have the same number of vowels (`'a'`, `'e'`, `'i'`, `'o'`, `'u'`, `'A'`, `'E'`, `'I'`, `'O'`, `'U'`). Notice that `s` contains uppercase and lowercase letters.<br />
<br />Return `true`<em> if </em>`a`<em> and </em>`b`<em> are **alike**</em>. Otherwise, return `false`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: s = "book"
Output: true
Explanation: a = "b<u>o</u>" and b = "<u>o</u>k". a has 1 vowel and b has 1 vowel. Therefore, they are alike.
```
<br />**Example 2:**<br />
```
Input: s = "textbook"
Output: false
Explanation: a = "t<u>e</u>xt" and b = "b<u>oo</u>k". a has 1 vowel whereas b has 2. Therefore, they are not alike.
Notice that the vowel o is counted twice.
```
<br /> <br />
<br />**Constraints:**<br />

* `2 <;= s.length <;= 1000`

* `s.length` is even.

* `s` consists of **uppercase and lowercase** letters.