# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X

## Program:
(i) To find the L and U matrix
```
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
/*
Program to find the L and U matrix.
Developed by: MIDHUN S
RegisterNumber: 212224230158
*/
```
(ii) To find the LU Decomposition of a matrix
```
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu, piv), b)
print(X)
/*
Program to find the LU Decomposition of a matrix.
Developed by: MIDHUN S
RegisterNumber: 212224230158
*/
```

## Output:
![Screenshot 2025-04-26 112733](https://github.com/user-attachments/assets/bde04d73-41ff-4635-b890-4494bf7d4fec)
![Screenshot 2025-04-26 112744](https://github.com/user-attachments/assets/a29f0438-bd45-4ded-98ed-00c472168405)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

