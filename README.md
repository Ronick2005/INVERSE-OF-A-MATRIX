# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1 : Import numpy library as np.
### Step 2: Create a matrix using array() function.
### Step 3: Using the np.linalg.inv(), we get the inverse of the given matrix.
### Step 4: Get the output and end the program.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by: Ronick Aakshath P
#RegisterNumber: 22007303

import numpy as np

a = np.array([[1, 0, 3], [-1, 2, -2], [2, 3, -1]])
mat_inv = np.linalg.inv(a)
print(mat_inv)
```
## Output:
![output](inv_mat_output.png)
## Result:
Thus the inverse of given matrix is successfully solved using python program
