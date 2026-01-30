# EIGENVALUES-AND-EIGENVECTORS
## Devoloped by: CHIDROOP M J
## Register number: 25018548
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```python
import numpy as np

X=[-2,2,-3],[2,1,-6],[-1,-2,0]
value,vector=np.linalg.eig(X)
print(f"Eigen values are {value} and Eigen Vectors are {vector}")
```
## Output:

<img width="1345" height="854" alt="image" src="https://github.com/user-attachments/assets/d4982288-fe2f-43b9-9af7-968eebaee78c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
