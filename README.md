# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library.
2. Import lu function from scipy library.
3. Solve LU decomposition using lu_solve() function.
4. print the value.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Yuvaram
RegisterNumber:24900232
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Yuvaram
RegisterNumber:24900232
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),b)
print(X)
*/
```

## Output:
![lu decomposition]()
![Screenshot 2024-11-27 121505](https://github.com/user-attachments/assets/0064ba69-b803-4bb3-b36f-08d1defb3936)
![Screenshot 2024-11-27 121517](https://github.com/user-attachments/assets/48fd3fe0-458b-484b-bbfb-57e6e3632645)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

