# 748. Shortest Completing Word

<br />Given a string `licensePlate` and an array of strings `words`, find the **shortest completing** word in `words`.<br />
<br />A **completing** word is a word that **contains all the letters** in `licensePlate`. **Ignore numbers and spaces** in `licensePlate`, and treat letters as **case insensitive**. If a letter appears more than once in `licensePlate`, then it must appear in the word the same number of times or more.<br />
<br />For example, if `licensePlate`` = "aBc 12c"`, then it contains letters `'a'`, `'b'` (ignoring case), and `'c'` twice. Possible **completing** words are `"abccdef"`, `"caaacab"`, and `"cbca"`.<br />
<br />Return <em>the shortest **completing** word in </em>`words`<em>.</em> It is guaranteed an answer exists. If there are multiple shortest **completing** words, return the **first** one that occurs in `words`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: licensePlate = "1s3 PSt", words = ["step","steps","stripe","stepple"]
Output: "steps"
Explanation: licensePlate contains letters 's', 'p', 's' (ignoring case), and 't'.
"step" contains 't' and 'p', but only contains 1 's'.
"steps" contains 't', 'p', and both 's' characters.
"stripe" is missing an 's'.
"stepple" is missing an 's'.
Since "steps" is the only word containing all the letters, that is the answer.
```
<br />**Example 2:**<br />
```
Input: licensePlate = "1s3 456", words = ["looks","pest","stew","show"]
Output: "pest"
Explanation: licensePlate only contains the letter 's'. All the words contain 's', but among these "pest", "stew", and "show" are shortest. The answer is "pest" because it is the word that appears earliest of the 3.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= licensePlate.length <;= 7`

* `licensePlate` contains digits, letters (uppercase or lowercase), or space `' '`.

* `1 <;= words.length <;= 1000`

* `1 <;= words[i].length <;= 15`

* `words[i]` consists of lower case English letters.