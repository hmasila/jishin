# 762. Prime Number of Set Bits in Binary Representation

<br />Given two integers `left` and `right`, return <em>the **count** of numbers in the **inclusive** range </em>`[left, right]`<em> having a **prime number of set bits** in their binary representation</em>.<br />
<br />Recall that the **number of set bits** an integer has is the number of `1`'s present when written in binary.<br />

* For example, `21` written in binary is `10101`, which has `3` set bits.


<br /> <br />
<br />**Example 1:**<br />
```
Input: left = 6, right = 10
Output: 4
Explanation:
6  ->; 110 (2 set bits, 2 is prime)
7  ->; 111 (3 set bits, 3 is prime)
8  ->; 1000 (1 set bit, 1 is not prime)
9  ->; 1001 (2 set bits, 2 is prime)
10 ->; 1010 (2 set bits, 2 is prime)
4 numbers have a prime number of set bits.
```
<br />**Example 2:**<br />
```
Input: left = 10, right = 15
Output: 5
Explanation:
10 ->; 1010 (2 set bits, 2 is prime)
11 ->; 1011 (3 set bits, 3 is prime)
12 ->; 1100 (2 set bits, 2 is prime)
13 ->; 1101 (3 set bits, 3 is prime)
14 ->; 1110 (3 set bits, 3 is prime)
15 ->; 1111 (4 set bits, 4 is not prime)
5 numbers have a prime number of set bits.
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= left <;= right <;= 10<sup>6</sup>`

* `0 <;= right - left <;= 10<sup>4</sup>`