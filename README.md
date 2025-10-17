# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import required libraries.
### Step 2: 
Define the matrix for which you want to find eigenvalues and eigenvectors.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
Print the results.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: ARANI VENKATA SUNDARA LEELA KRISHNA
#RegisterNumber:212224240013

import numpy as np
a=np.array([[4,2],[2,4]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {}'.format(values,vectors))
```
## Output:
<img width="1755" height="1990" alt="image" src="https://github.com/user-attachments/assets/67399124-f4c3-481d-90da-e526a577f891" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
