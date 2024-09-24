# DATE:

# EX:NO.4 EIGENVALUES AND EIGENVECTORS

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

## Step1 : 
### import numpy as np
## Step 2: 
### Define the matrix 'a'
## Step 3: 
### Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
## Step 4: 
### Print the eigenvalues and eigenvectors


## Program:


```
#Program to find the eigen values and eigen vectors.
#Developed by: KAVI NILAVAN DK
#RegisterNumber: 212223230103

import numpy as np
a=[-2,2,-3],[2,1,-6],[-1,-2,0]
values,vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```


## Output:
![image](https://github.com/user-attachments/assets/0b186b97-acde-41a1-ac46-e8b5cae7f63c)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
