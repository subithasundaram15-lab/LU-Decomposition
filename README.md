# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Read the input matrix (and right-hand side vector for solving equations) from the user.
2.Convert the given input into a NumPy array.
3.Apply LU decomposition to factorize the matrix into Lower triangular matrix (L) and Upper triangular matrix (U).
4.Display the L and U matrices, and if required, solve the system of linear equations using the decomposed matrices. 

## Program:
(i) To find the L and U matrix
```
Developed by: SUBITHA S
RegisterNumber: 212225040432
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
Developed by: SUBITHA S
RegisterNumber: 212225040432
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
<img width="646" height="170" alt="image" src="https://github.com/user-attachments/assets/9bb077d3-1e92-4590-92af-1eb25c9bf570" />
<img width="895" height="347" alt="image" src="https://github.com/user-attachments/assets/e68f71b5-d6d0-4f9a-b307-5a86981f5a39" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

