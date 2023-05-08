# 1025. Divisor Game

<br />Alice and Bob take turns playing a game, with Alice starting first.<br />
<br />Initially, there is a number `n` on the chalkboard. On each player's turn, that player makes a move consisting of:<br />

* Choosing any `x` with `0 <; x <; n` and `n % x == 0`.

* Replacing the number `n` on the chalkboard with `n - x`.


<br />Also, if a player cannot make a move, they lose the game.<br />
<br />Return `true` <em>if and only if Alice wins the game, assuming both players play optimally</em>.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: n = 2
Output: true
Explanation: Alice chooses 1, and Bob has no more moves.
```
<br />**Example 2:**<br />
```
Input: n = 3
Output: false
Explanation: Alice chooses 1, Bob chooses 1, and Alice has no more moves.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= n <;= 1000`