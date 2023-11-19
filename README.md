# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculations.
### Step 2: 
Prepare the lists from each equations and assign in np.array()
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
end the program
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:BOOBESH PM 
#RegisterNumber:212222233001
import numpy as np
A=np.array([[2,2],[1,3]])
values,vactors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vactors))
```
## Output:
![mat 4](https://github.com/Boobeshkrishna/EIGENVALUES-AND-EIGENVECTORS/assets/141472052/9fb86e9c-a41a-4a8d-b36e-f4268b9b6220)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
