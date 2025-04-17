# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:Start with a given matrix A of size m × n (m rows, n columns). 
### Step 2:Convert the matrix to row echelon form (REF) using elementary row operations: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: The number of non-zero rows in REF is the rank of the matrix.
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Ethicvaran S
#RegisterNumber:24011973
import numpy as np
A =  [[1,2,3],[3,6,9]]
B = np.linalg.matrix_rank(A)
print(B)
```
## Output:
![alt text](<Screenshot 2025-04-17 142750.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

