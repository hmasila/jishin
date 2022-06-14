# 1436. Destination City

<br />You are given the array `paths`, where `paths[i] = [cityA<sub>i</sub>, cityB<sub>i</sub>]` means there exists a direct path going from `cityA<sub>i</sub>` to `cityB<sub>i</sub>`. <em>Return the destination city, that is, the city without any path outgoing to another city.</em><br />
<br />It is guaranteed that the graph of paths forms a line without any loop, therefore, there will be exactly one destination city.<br />
<br /> <br />
<br />**Example 1:**<br />
```
Input: paths = [["London","New York"],["New York","Lima"],["Lima","Sao Paulo"]]
Output: "Sao Paulo" 
Explanation: Starting at "London" city you will reach "Sao Paulo" city which is the destination city. Your trip consist of: "London" ->; "New York" ->; "Lima" ->; "Sao Paulo".
```
<br />**Example 2:**<br />
```
Input: paths = [["B","C"],["D","B"],["C","A"]]
Output: "A"
Explanation: All possible trips are: 
"D" ->; "B" ->; "C" ->; "A". 
"B" ->; "C" ->; "A". 
"C" ->; "A". 
"A". 
Clearly the destination city is "A".
```
<br />**Example 3:**<br />
```
Input: paths = [["A","Z"]]
Output: "Z"
```
<br /> <br />
<br />**Constraints:**<br />

* `1 <;= paths.length <;= 100`

* `paths[i].length == 2`

* `1 <;= cityA<sub>i</sub>.length, cityB<sub>i</sub>.length <;= 10`

* `cityA<sub>i</sub> != cityB<sub>i</sub>`

* All strings consist of lowercase and uppercase English letters and the space character.