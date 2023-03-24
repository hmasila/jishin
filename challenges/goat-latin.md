# 824. Goat Latin

<br />You are given a string `sentence` that consist of words separated by spaces. Each word consists of lowercase and uppercase letters only.<br />
<br />We would like to convert the sentence to "Goat Latin" (a made-up language similar to Pig Latin.) The rules of Goat Latin are as follows:<br />

<li>If a word begins with a vowel (`'a'`, `'e'`, `'i'`, `'o'`, or `'u'`), append `"ma"` to the end of the word.

	
* For example, the word `"apple"` becomes `"applema"`.


</li>
<li>If a word begins with a consonant (i.e., not a vowel), remove the first letter and append it to the end, then add `"ma"`.
	
* For example, the word `"goat"` becomes `"oatgma"`.


</li>
<li>Add one letter `'a'` to the end of each word per its word index in the sentence, starting with `1`.
	
* For example, the first word gets `"a"` added to the end, the second word gets `"aa"` added to the end, and so on.


</li>

<br />Return<em> the final sentence representing the conversion from sentence to Goat Latin</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: sentence = "I speak Goat Latin"
Output: "Imaa peaksmaaa oatGmaaaa atinLmaaaaa"
```<br />**Example 2:**<br />
```
Input: sentence = "The quick brown fox jumped over the lazy dog"
Output: "heTmaa uickqmaaa rownbmaaaa oxfmaaaaa umpedjmaaaaaa overmaaaaaaa hetmaaaaaaaa azylmaaaaaaaaa ogdmaaaaaaaaaa"
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= sentence.length <;= 150`

* `sentence` consists of English letters and spaces.

* `sentence` has no leading or trailing spaces.

* All the words in `sentence` are separated by a single space.