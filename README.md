# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy library using import statement.

2.From scipy package import lu().

3.Get input from user and pass it as an array.

4.Get P, L, U matrix using lu().

5.Print L and U matrix.



## Program:
(i) To find the L and U matrix
```py
'''Program to find L and U matrix using LU decomposition.
Developed by: M THEJESWARAN
RegisterNumber: 212223240168

'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```py
'''Program to solve a matrix using LU decomposition.
Developed by: M THEJESWARAN
RegisterNumber: 212223240168
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![Screenshot (32)](https://github.com/TEJA19092005/LU-Decomposition/assets/164043042/2cc6f57f-98ea-435f-a095-800a9d03823f)

![Screenshot (33)](https://github.com/TEJA19092005/LU-Decomposition/assets/164043042/46114881-962d-40be-9260-728ad3f80365)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

