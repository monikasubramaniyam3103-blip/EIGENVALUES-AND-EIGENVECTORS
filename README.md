# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :write a python program for the given matrix 
### Step 2:using numpy library
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4:run the given code

## Program:
import numpy as np

# Given matrix
A = np.array([[2, 2],
              [1, 3]])

# Find eigenvalues and eigenvectors
eigen_values, eigen_vectors = np.linalg.eig(A)

# Print result
print("Eigen values are", eigen_values, "and Eigen Vectors are", eigen_vectors)

## Output:
<img width="1260" height="764" alt="Screenshot 2026-02-05 141223" src="https://github.com/user-attachments/assets/6dc3924f-2292-45b3-ab87-b2703697b475" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
