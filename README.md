# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the NumPy library to perform numerical and matrix operations.
### Step 2: 
Define the matrix using a 2D NumPy array with np.array().
### Step 3: 
Call np.linalg.eig() with the matrix as input.
### Step 4: 
Display both the eigenvalues and eigenvectors using the print() function.
### Step 5:
End the program.
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: Hariharan M
#RegisterNumber:24900770

import numpy as np
b=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
val,vec=np.linalg.eig(b)
print("Eigen values are {} and Eigen Vectors are {}".format(val,vec))
```
## Output:
![exma4](https://github.com/user-attachments/assets/1c2991dc-8736-4ba2-98c9-ca74b909b958)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
