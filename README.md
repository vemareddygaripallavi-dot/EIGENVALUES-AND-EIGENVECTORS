# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :Import the numpy module to use the built-in functions for calculation 
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Vemareddygari Pallavi
#RegisterNumber:212225230293
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
eig_values,eig_vectors=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eig_values,eig_vectors))
```
## Output:
<img width="1504" height="767" alt="image" src="https://github.com/user-attachments/assets/9fda66c4-0ff5-4352-9a62-b79bf8a1d077" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
