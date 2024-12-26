# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:1
1.Step1: import numpy and scipy.linalg ,in linalg you can input lu. and in second program can import lu_factor and lu_solve from python library as same as in second program

2.Step2: Get input from user as the form of nested list to compute numpy array format

3.Step3: Use inputted array (matrix) to compute in corresponding bultin modules function such as lu and create new variable such as piv,l_matrix,u_matrix to store result

4.Step4: Print the corresponding bvariable to get output (l_matrix)

5.Step5: Print the corresponding bvariable to get output (u_matrix)
## Algorithm:2
1.Step1: In second program can import lu_factor and lu_solve from python library as same as in second program.

2.Step2: Get the input from user in the form of nested list to compute numpy array format and declare it for both the variables.

3.Step3: Create the varaiable to Use inputted array to compute of lu_factor of matrix varaible

4.Step4: Create the new variable for lu_solve to compute of 'x' varaiable and 'b' variable

5.Step5: Print the corresponding variable (solution) to get output


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by:B.selvaganesh
RegisterNumber: 24900817
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: B.selvaganesh
RegisterNumber: 24900817
'''

import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
```

## Output:
![lu decomposition](exp.05.png)
![lu decomposition](exp.005.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

