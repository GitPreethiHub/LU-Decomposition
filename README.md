# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement.
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L, U matrix using lu().
5. Print L and U matrix

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: Preethi M
RegisterNumber: 212222100037
'''
import numpy as np
import scipy.linalg
mat=eval(input())
a=np.array(mat)
p,l,u=scipy.linalg.lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: Preethi M
RegisterNumber: 212222100037
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a,b=eval(input()),eval(input())
c=lu_solve(lu_factor(a),b)
print(c)
```

## Output:
![image](https://github.com/GitPreethiHub/LU-Decomposition/assets/119475585/aa2e66d0-6752-4731-9a4b-1f661741b1e4)

![image](https://github.com/GitPreethiHub/LU-Decomposition/assets/119475585/a310d434-6ff8-4045-aea0-62b66a089908)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

