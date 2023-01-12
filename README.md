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
![Screenshot 2023-01-12 at 09-26-16 Ex05-CR- LU Decomposition Attempt review](https://user-images.githubusercontent.com/118708624/212016291-c57e4a51-8fc7-4b95-8d68-e0252c8faf03.png)

![Screenshot 2023-01-12 at 09-29-49 Ex05-CR- LU Decomposition Attempt review](https://user-images.githubusercontent.com/118708624/212016357-56c95dea-d8b3-4cea-875d-b49439ef3636.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

