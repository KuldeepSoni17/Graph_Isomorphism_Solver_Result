# Graph Isomorphism Solver Result</br>
Graph Isomorphism Solver solves the graph isomorphism problem in polynomial time.</br>
Algorithm will be available once mathematically proved.</br>
Here is testing result performed on 470,000+ random instances and also on benchmark algorithms.
### Reading result files

1st line shows number of nodes.

next n line contains n*n adjacency matrix representing graph.

next line contains a permutation of node list

next n line contains mapping of old graphs with new graphs.

next line shows result "SIMILAR" or "DISSIMILAR"

SIMILAR if all nodes get mapped, otherwise DISSIMILAR.

### Example:-</br>
Number of nodes
###  10</br></br>
Adjacency Matrix
###  0 1 1 1 0 1 0 1 1 0 </br>
###  1 0 0 0 1 0 0 0 0 0 </br>
###  1 0 0 1 1 0 1 0 1 1 </br>
###  1 0 1 0 0 1 1 0 1 0 </br>
###  0 1 1 0 0 1 1 1 0 0 </br>
###  1 0 0 1 1 0 1 0 1 0 </br>
###  0 0 1 1 1 1 0 1 0 1 </br>
###  1 0 0 0 1 0 1 0 1 0 </br>
###  1 0 1 1 0 1 0 1 0 1 </br>
###  0 0 1 0 0 0 1 0 1 0 </br></br>

Permuted node list
###  0 5 4 3 2 6 9 7 1 8 </br></br>

Mapped list from old - new
### 0 0</br>
### 1 8</br>
### 2 4</br>
### 3 3</br>
### 4 2</br>
### 5 1</br>
### 6 5</br>
### 7 7</br>
### 8 9</br>
### 9 6</br></br>
Similar as all node found their correct mapping
### SIMILAR</br></br>
### Result verification</br></br>
0 0</br>
0th node gets placed at 0th position after permutation for new graph</br>
1 8</br>
1st node gets placed at 8th position after permutation for new graph</br>
2 4</br>
2nd node gets placed at 4th position after permutation for new graph</br>
and so.</br>

