# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step 1:start
step 2:get an input from user
step 3: display the value
step 4:stop

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: kaviya shree
RegisterNumber: 22002839
'''
import numpy as np
from scipy.linalg import lu
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: kaviya shree
RegisterNumber: 22002839
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=eval(input())
res=lu_factor(A)
solution=lu_solve(res,B)
print(solution)
*/
```

## Output:
![image](https://user-images.githubusercontent.com/120553351/215086504-86837b20-8811-447b-bfe6-e9c92d979e26.png)
![image](https://user-images.githubusercontent.com/120553351/215086574-2ef007ca-c512-48bc-94c6-3353fea0ef6e.png)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

