# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculations
### Step 2: Prepare the lists from each equation and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
#Program to find the eigen values and eigen vectors.
#Developed by: magesh s
#RegisterNumber:212225230160
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
<img width="1239" height="742" alt="Screenshot 2026-02-11 105616" src="https://github.com/user-attachments/assets/e6d1894c-a542-484d-bdcc-1b7aeb6f35f8" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
