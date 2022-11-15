# 1880. Check if Word Equals Summation of Two Words

<br />The **letter value** of a letter is its position in the alphabet **starting from 0** (i.e. `'a' ->; 0`, `'b' ->; 1`, `'c' ->; 2`, etc.).<br />
<br />The **numerical value** of some string of lowercase English letters `s` is the **concatenation** of the **letter values** of each letter in `s`, which is then **converted** into an integer.<br />

* For example, if `s = "acb"`, we concatenate each letter's letter value, resulting in `"021"`. After converting it, we get `21`.


<br />You are given three strings `firstWord`, `secondWord`, and `targetWord`, each consisting of lowercase English letters `'a'` through `'j'` **inclusive**.<br />
<br />Return `true` <em>if the **summation** of the **numerical values** of </em>`firstWord`<em> and </em>`secondWord`<em> equals the **numerical value** of </em>`targetWord`<em>, or </em>`false`<em> otherwise.</em><br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: firstWord = "acb", secondWord = "cba", targetWord = "cdb"
Output: true
Explanation:
The numerical value of firstWord is "acb" ->; "021" ->; 21.
The numerical value of secondWord is "cba" ->; "210" ->; 210.
The numerical value of targetWord is "cdb" ->; "231" ->; 231.
We return true because 21 + 210 == 231.
```
<br />**Example 2:**<br />
```
Input: firstWord = "aaa", secondWord = "a", targetWord = "aab"
Output: false
Explanation: 
The numerical value of firstWord is "aaa" ->; "000" ->; 0.
The numerical value of secondWord is "a" ->; "0" ->; 0.
The numerical value of targetWord is "aab" ->; "001" ->; 1.
We return false because 0 + 0 != 1.
```
<br />**Example 3:**<br />
```
Input: firstWord = "aaa", secondWord = "a", targetWord = "aaaa"
Output: true
Explanation: 
The numerical value of firstWord is "aaa" ->; "000" ->; 0.
The numerical value of secondWord is "a" ->; "0" ->; 0.
The numerical value of targetWord is "aaaa" ->; "0000" ->; 0.
We return true because 0 + 0 == 0.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= firstWord.length, ``secondWord.length, ``targetWord.length <;= 8`

* `firstWord`, `secondWord`, and `targetWord` consist of lowercase English letters from `'a'` to `'j'` **inclusive**.