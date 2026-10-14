# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy library
### Step 2: Define the square matrix a using np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:Print the eigenvalues and eigenvectors 

## Program:import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a=np.array([[4,2],[2,4]])

values,Vectors=np.linalg.eig(a)

print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:<img width="1269" height="787" alt="{947035CF-1F61-4E08-92B4-6847A0EC488C}" src="https://github.com/user-attachments/assets/e1e0e5e4-0229-461f-b33f-50d763c73ef3" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
