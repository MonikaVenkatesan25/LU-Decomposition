# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition.
Developed by: Monika V
RegisterNumber: 212225100028
/*
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Monika V
RegisterNumber: 212225100028
*/
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
<img width="1164" height="628" alt="image" src="https://github.com/user-attachments/assets/059a8fe0-b1b2-43b8-be29-321e09599d0a" />

<img width="1161" height="666" alt="image" src="https://github.com/user-attachments/assets/3601186d-f0d3-4030-8d39-75433e212f25" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

