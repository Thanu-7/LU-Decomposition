# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy module from python library
2. import lu from scipy.linalg and get the l and u matrices.
3. from scipy.linalg import lu_factor and lu_solve to get lu decomposition.
4. Display the value using print function.

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Thanushree Vijayakanth
RegisterNumber: 24900679

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
Developed by: Thanushree Vijayakanth
RegisterNumber: 24900679

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
X=lu_solve((lu,piv),b)
print(X)


*/
```

## Output:
![rec5](https://github.com/user-attachments/assets/d2904799-804a-4902-a8f4-f32a61534b2b)
![rec51](https://github.com/user-attachments/assets/7532d769-b76b-4e37-b7cc-f60aebad125e)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

