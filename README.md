# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program.
### Step 2: Import NumPy and define the matrix a.

### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Display the eigen values and eigen vectors, then stop the program.


## Program:
```
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))

```
## Output:
<img width="938" height="435" alt="Screenshot 2026-05-20 133922" src="https://github.com/user-attachments/assets/930229ed-1b5c-4699-ba62-642704df6229" />
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
