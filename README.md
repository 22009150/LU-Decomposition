# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
step1:
import the numpy module to use the built in function for calculation

step2:
preparethe lists from each linear equation and assign in np.array()

step3:
from scipy.linalg import lu we can find the solutions.

step4:
End the program


## Program:
(i) To find the L and U matrix

'''Program to find L and U matrix using LU decomposition.
Developed by: Archana.k
RegisterNumber: 22009150
'''
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Archana.k
RegisterNumber: 22009150
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)

## Output:
![lu decomposition]()
![image](https://user-images.githubusercontent.com/118708624/211973356-01f47620-0ebb-4097-b6e1-328e6f6c6278.png)
![image](https://user-images.githubusercontent.com/118708624/211973410-b5356e20-326e-4dfa-b6f9-66ebb5b85888.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

