# 804. Unique Morse Code Words

<br />International Morse Code defines a standard encoding where each letter is mapped to a series of dots and dashes, as follows:<br />

* `'a'` maps to `".-"`,

* `'b'` maps to `"-..."`,

* `'c'` maps to `"-.-."`, and so on.


<br />For convenience, the full table for the `26` letters of the English alphabet is given below:<br />
```[".-","-...","-.-.","-..",".","..-.","--.","....","..",".---","-.-",".-..","--","-.","---",".--.","--.-",".-.","...","-","..-","...-",".--","-..-","-.--","--.."]```
<br />Given an array of strings `words` where each word can be written as a concatenation of the Morse code of each letter.<br />

* For example, `"cab"` can be written as `"-.-..--..."`, which is the concatenation of `"-.-."`, `".-"`, and `"-..."`. We will call such a concatenation the **transformation** of a word.


<br />Return <em>the number of different **transformations** among all words we have</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: words = ["gin","zen","gig","msg"]
Output: 2
Explanation: The transformation of each word is:
"gin" ->; "--...-."
"zen" ->; "--...-."
"gig" ->; "--...--."
"msg" ->; "--...--."
There are 2 different transformations: "--...-." and "--...--.".
```
<br />**Example 2:**<br />
```
Input: words = ["a"]
Output: 1
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= words.length <;= 100`

* `1 <;= words[i].length <;= 12`

* `words[i]` consists of lowercase English letters.