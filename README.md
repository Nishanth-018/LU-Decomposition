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
Program to find the L and U matrix.
Developed by: Nishanth J
RegisterNumber:23007929
*/
'''Program to find L and U matrix using LU decomposition.
Developed by:Nishanth J 
RegisterNumber:23007929
'''
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
Developed by:Nishanth J
RegisterNumber:23007929
*/
'''Program to solve a matrix using LU decomposition.
Developed by:Nishanth J
RegisterNumber:23007929
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A= np.array(eval(input()))
b= np.array(eval(input()))
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)

```

## Output:
![Screenshot 2023-12-31 223731](https://github.com/Nishanth-018/LU-Decomposition/assets/149347651/0f861d67-c60b-483e-9335-937bd6850faf)
![Screenshot 2023-12-31 223917](https://github.com/Nishanth-018/LU-Decomposition/assets/149347651/1422d744-e4c5-4962-a6ef-11310bce1f12)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

