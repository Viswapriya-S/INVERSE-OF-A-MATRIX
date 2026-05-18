# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the Program

## Program:
```Python
#Program to find the inverse of a matrix.
#Developed by: Viswapriya S
#RegisterNumber: 212225230311
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]]) 
X=np.linalg.inv(A) 
print(X)
```
## Output:

<img width="1277" height="842" alt="image" src="https://github.com/user-attachments/assets/770c25a9-56bb-4397-b604-63b01b332648" />
<img width="1280" height="367" alt="image" src="https://github.com/user-attachments/assets/f97cb9ae-9817-403d-94c9-f6eb1e097401" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

