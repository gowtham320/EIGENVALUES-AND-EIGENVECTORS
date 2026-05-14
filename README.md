# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()

### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: gowtham u
#RegisterNumber:212225040099
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,2],[1,3]])
x,y=np.linalg.eig(a)
print(f"Eigen values are {x} and Eigen Vectors are {y}")
```

## Output:
<img width="725" height="205" alt="image" src="https://github.com/user-attachments/assets/4a56fff0-e802-4aa9-a9ab-e01c9facfbc5" />
<img width="730" height="206" alt="image" src="https://github.com/user-attachments/assets/75dd9e73-5334-484f-ba23-b7c94f6aff83" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
