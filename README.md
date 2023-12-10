# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Use LU decomposition to factorize the coefficient matrix A into two matrices L(lower triangular) and U (Upper Triangular)


2. Solve for Y in LY=B
3. Solve for X in UX=Y
4. The solution matrix X contains the values of the variables that satisfies the system of linear equations.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: SHAIK MAHAMMAD IMRAAN
RegisterNumber: 23011682
*/
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: SHAIK MAHAMMAD IMRAAN
RegisterNumber: 23011682
*/
```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)

## Output:
![lu decomposition]()
![image](https://github.com/AkilaMohan/LU-Decomposition/assets/149347407/c8e0f8d0-615b-472b-9119-2542fd7c323c)


![image](https://github.com/AkilaMohan/LU-Decomposition/assets/149347407/d955b6d3-6bac-420c-8af2-2ae13169762b)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

