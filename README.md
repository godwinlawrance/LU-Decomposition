# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Start the program

2.Import the necessary libraries(numpy,scipy.linalg)

3.Define the matrix using numpy

4.Use lu(),lu_solve(),lu_factor() to get the solutions

5.End the program.  

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Godwin Lawrance L
RegisterNumber: 212225220034
'''
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Godwin Lawrance L
RegisterNumber: 212225220034
'''

# To print X matrix (solution to the equation)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
<img width="1918" height="867" alt="image" src="https://github.com/user-attachments/assets/b36bb8e9-c5be-4e77-965b-ae6abe83f0b3" />

<img width="1885" height="844" alt="image" src="https://github.com/user-attachments/assets/9c7c1c7e-6a39-4323-8073-c09bb1c9d03a" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

