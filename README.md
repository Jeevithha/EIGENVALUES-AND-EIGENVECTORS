# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

### Step1 : 
import the numpy module to use the built in functions for calculation.

### Step 2: 
prepare the lists from each linear equations and assign in np.array().

### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4: 
End the module

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:jeevitha S
#RegisterNumber:212222100016
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```
## Output:
![Screenshot (97)](https://user-images.githubusercontent.com/123623197/227888910-affdba23-022d-466f-9b67-a042527f75a8.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
