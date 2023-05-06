# 1128. Number of Equivalent Domino Pairs

<br />Given a list of `dominoes`, `dominoes[i] = [a, b]` is **equivalent to** `dominoes[j] = [c, d]` if and only if either (`a == c` and `b == d`), or (`a == d` and `b == c`) - that is, one domino can be rotated to be equal to another domino.<br />
<br />Return <em>the number of pairs </em>`(i, j)`<em> for which </em>`0 <;= i <; j <; dominoes.length`<em>, and </em>`dominoes[i]`<em> is **equivalent to** </em>`dominoes[j]`.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: dominoes = [[1,2],[2,1],[3,4],[5,6]]
Output: 1
```
<br />**Example 2:**<br />
```
Input: dominoes = [[1,2],[1,2],[1,1],[1,2],[2,2]]
Output: 3
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= dominoes.length <;= 4 * 10<sup>4</sup>`

* `dominoes[i].length == 2`

* `1 <;= dominoes[i][j] <;= 9`