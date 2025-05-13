# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from the matrix and assign in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program.
## Program:
```
#Program to find the solution for the given linear equations.
#Developed by: MATHAVAN V
#RegisterNumber:  212223110026

import numpy as np
a=np.array([[1,2,3],[3,6,9]])
sol=np.linalg.matrix_rank(a)
print(sol)
```
![image](https://github.com/user-attachments/assets/6eba36b1-f78f-42aa-9100-dc4aa25dae82)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
