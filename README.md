# knapsack

This is a C++ implementation of the 0/1 knapsack problem.

The example solves this problem: https://www.youtube.com/watch?v=EH6h7WA7sDw

Output of the example problem:
```
Knapsack current state
Size: 5 Item count: 3
{ Weight: 3, Value: 5 }
{ Weight: 2, Value: 3 }
{ Weight: 1, Value: 4 }

Value matrix: 
V   1 2 3 4 5 
    - - - - -
0 | 0 0 0 0 0 
1 | 0 0 5 5 5 
2 | 0 3 5 5 8 
3 | 4 4 7 9 9 

Keep matrix: 
K   1 2 3 4 5 
    - - - - -
0 | 0 0 0 0 0 
1 | 0 0 1 1 1 
2 | 0 1 0 0 1 
3 | 1 1 1 1 1 
```
