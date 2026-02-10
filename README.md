# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
import numpy as np
A = np.array([[-2,  2, -3],[ 2,  1, -6],[-1, -2,  0]])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:
<img width="1322" height="655" alt="mathematicsforai-ex-4" src="https://github.com/user-attachments/assets/185f1ee3-4bef-453e-9d0d-b4afa6e7f4fe" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
