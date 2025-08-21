# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
3. 	
## Algorithm:
### Step1 : Define the square matrix A waith given elements.
### Step 2: Store the elements in a NumPy array for performing matrix operations
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the eigenvalues and corresponding eigenvectors as output.

## Program:
import numpy as np

A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])

values,vectors=np.linalg.eig(A)

print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))

## Output:
<img width="1255" height="321" alt="image" src="https://github.com/user-attachments/assets/402bf59c-d2d7-4e3e-b870-321cf35f752a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
