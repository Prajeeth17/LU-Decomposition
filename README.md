# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

## Step 1:
Import numpy package
## Step 2:
Get the input matrix
## Step 3:
Find the LU decomposition of the given matrix
## Step 4:
Print the result

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: Prajeeth K T
RegisterNumber: 22002267
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```python
'''Program to solve a matrix using LU decomposition.
Developed by: Prajeeth K T
RegisterNumber: 22002267
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![lu decomposition](./Lu%20matrix.jpg)
![](./Lu%20solve.jpg)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

