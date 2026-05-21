# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:G. Shawn Ronel
#RegisterNumber:25005544
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
val,vec=np.linalg.eig(A)
print(f"Eigen values are {val} and Eigen Vectors are {vec}")
```
## Output:
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/c368d888-9ed2-48fe-8bbd-45acbf8e24f4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
