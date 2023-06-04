# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as "X" include the package in that variable.
4.Print the variable "X".

## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Yeshwanth P
RegisterNumber: 212222230178
import numpy as np
from scipy.linalg import lu
arr=np.array(eval(input()))
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber: 
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
(i) To find the L and U matrix
![Screenshot 2023-06-04 134235](https://github.com/Yeshwanthperumal/LU-Decomposition/assets/119476088/ba4c5638-6006-44c0-80d0-290b4c33b8f5)

(ii) To find the LU Decomposition of a matrix
![Screenshot 2023-06-04 134305](https://github.com/Yeshwanthperumal/LU-Decomposition/assets/119476088/036a12da-d396-42bd-8db2-d4bec56a7272)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
