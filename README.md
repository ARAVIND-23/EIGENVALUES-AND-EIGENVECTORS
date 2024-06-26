# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built in function in the calculations .
### Step 2: 
Prepare the lists from each equation and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:
End the program

## Program:
import numpy as np
matrix=np.array(([2,2],[1,3]))
eigenvalues,eigenvectors=np.linalg.eig(matrix)
print(f"Eigen values are {eigenvalues} and Eigen Vectors are {eigenvectors}")

## Output:
![Screenshot 2024-04-15 193741](https://github.com/ARAVIND-23/EIGENVALUES-AND-EIGENVECTORS/assets/138970182/592f76f8-64ae-41d0-be72-0ea1799ef34a)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
