# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import the numpy module
2. imorting ly from scipy.linalg
3. getting input
4. eval and print the output

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: ILAIYADEEPAN . K
RegisterNumber: 23013535
'''
import numpy as np
from scipy.linalg import lu
A=eval(input())
P,L,U=lu(A)


print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: ILAIYADEEPAN . K
RegisterNumber: 23013535
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu,solve
A=eval(input())
B=eval(input())
P,L,U=lu(A)
x=solve(A,B)
print(x)
: 
*/
```

## Output:
![LU output1](https://github.com/ILAIYADEEPAN/LU-Decomposition/assets/147473334/c499830e-dc49-4a1c-a702-79b5aaef79b5)
![LU output2](https://github.com/ILAIYADEEPAN/LU-Decomposition/assets/147473334/013e51df-dab2-4542-9bdf-f3311cc94810)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

