# EXP 2 - RANK-OF-A-MATRIX
## Aim:
## DATE: 09.03.2024
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Importing the NumPy library using the statement import numpy as np.
### Step 2: Define a 3x3 matrix A with the specified values.
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: Display the rank of matrix A using the print() statement.
### Step 5: End the program.
## Program:
```
#write a program to find the solution to a system of linear equations [5,-3,-10],[2,2,-3],[-3,-1,5]

#prgram to find the rank of the matrix for the given matrix 
#devoleped by : poovarasu
#registerNumber:2305002017

import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(a)
print("the rank of the matrix a:",rank)
```
## Output:

![2](https://github.com/Poovarasu8/RANK-OF-A-MATRIX/assets/155505954/2d4dd50e-7627-4168-acce-34a2a3301187)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

