# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. TO FIND L AND U MATRICES WITH LU DEOMPOSITION
## STEP 1:
get the matrix from the user.
## STEP 2:
using "from scipy.linalg import lu"to import scipy (LU) module.
## STEP 3:
using "L,U=LU(a)" we can get the matrix of L and U.
## STEP 4:
print the result matrices (L and U) matrices.
## 2. to find X matrix with LU decomposition 
## STEP 1:
get the matrix from the user.
## step 2:
using "from scipy.linalg import lu_actor,lu_solve" to import scipy module for factorisation and solving X.
## step 3:
using "lu,piv=lu_factor(a)"
## step 4:
print the ouput(x matrix)
## step %:
ed the program.
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: mohammed faizal
RegisterNumber: 22003412
*/
```
```
import numpy as np
from scipy.linalg import lu
arr=eval(input ())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: mohammed faizal
RegisterNumber: 22003412
*/
```
```
import numpy as mp
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input())
B = np.array(eval(input())
lu,pivot = lu_factor(A  )
x = lu_solve(lu,pivot),B)
print(x)
```



## Output:
![output](/Screenshot%20from%202023-01-21%2020-46-35.png)
![output](/Screenshot%20from%202023-01-21%2020-47-17.png)
![lu decomposition]()


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

