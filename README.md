# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End of the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:Ragul S 
#RegisterNumber:212225230222

import numpy as np
A=np.array([[2,2],[1,3]])
v,va=np.linalg.eig(A)
print(f"Eigen values are {v} and Eigen Vectors are {va}")
```

## Output:
<img width="1245" height="204" alt="image" src="https://github.com/user-attachments/assets/a5437be7-ceb5-4778-81cf-41ba18a6e5ec" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
