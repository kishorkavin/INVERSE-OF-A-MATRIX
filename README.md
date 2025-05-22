# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Ensure the matrix is square and has a non-zero determinant.
### Step 2: Form the augmented matrix [A|I], where I is the identity matrix.
### Step 3: Use row operations to transform [A|I] into [I|A⁻¹].
### Step 4: Extract A⁻¹ from the right half of the resulting matrix.

## Program:
```
#Program to find the inverse of a matrix.
#Developed by:kishore kavin S 
#RegisterNumber:24005324
import numpy as np
A= np.array([[6, 2, 3],[3 , 1, 1],[10, 3, 4]])
result= np.linalg.inv(A)
print(result)
```
## Output:
![image](https://github.com/user-attachments/assets/3d57c907-06c5-4ef1-b5db-37bb4483fa4a)

## Result:
Thus the inverse of given matrix is successfully solved using python program

