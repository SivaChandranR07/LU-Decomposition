# LU Decomposition 
## Aim:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
### 1.
Hardware – PCs
### 2.
Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm
### Step 1: 
import numpy as np
### Step 2:
get input from user
### Step 3:
apply lu decomposition formula
### Step 4:
print the output
## Program:
(i) To find the L and U matrix
``` python
Program to find L and U matrix using LU decomposition.
Developed by: Siva Chandran R
RegisterNumber: 22005531
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```python
Program to solve a matrix using LU decomposition.
Developed by: Siva Chandran R
RegisterNumber: 22005531
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =eval(input())
B =eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```
## Output:
![OUTPUT](ut7.png)
![OUTPUT](ut8.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.
