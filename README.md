# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program.

2. Read the square matrix A.

3. Apply LU decomposition on A.

4. Obtain L and U matrices.

5. Display the result.

6. Stop.

## Program:
(i) To find the L and U matrix
```python
'''Program to find L and U matrix using LU decomposition.
Developed by: Praveen Raj.R
RegisterNumber: 212224230207
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
Developed by: Praveen Raj.R
RegisterNumber:21224230207
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)

```

## Output:

<img width="1345" height="1047" alt="image" src="https://github.com/user-attachments/assets/5ae7ade2-f89f-4a73-8b4c-44454b3e7d82" />

<img width="1375" height="903" alt="image" src="https://github.com/user-attachments/assets/d69c28c7-3fe2-40d9-bbe0-50e3c63d59cd" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

