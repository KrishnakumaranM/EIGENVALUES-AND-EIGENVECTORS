# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Get the input matrix from the user
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: M KRISHNA KUMARAN
#RegisterNumber:212224110033
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
val,vect=np.linalg.eig(a)
print("Eigen values are",val,"and Eigen Vectors are",vect)
```


## Output:
![image](https://github.com/user-attachments/assets/02ece880-62ff-4e41-8401-f1ff0f22792b)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
