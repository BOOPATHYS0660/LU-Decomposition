# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
```
Step1: 
Define the package as scipy.linalg import lu.
Step2:
Get input from user and print L and U matrix by 'print' .
Step3:
Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
Step4: 
Print the variable 'X'
```
## Program:
(i) To find the L and U matrix
```
Program to find the L and U matrix.
Developed by: Boopathy S 
RegisterNumber: 2305003002

import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```
Program to find the LU Decomposition of a matrix.
Developed by: Boopathy S 
RegisterNumber: 2305003002 

import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
x= lu_solve((lu,piv),b)
print(x)
```
## Output:
![Screenshot 2024-05-01 180732](https://github.com/BOOPATHYS0660/LU-Decomposition/assets/155909381/33cec5d8-9a26-4f31-9bf0-af063fb0a0b7)
![Screenshot 2024-05-01 180754](https://github.com/BOOPATHYS0660/LU-Decomposition/assets/155909381/0b050caa-e4fb-4761-886a-7ac112235c3d)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

