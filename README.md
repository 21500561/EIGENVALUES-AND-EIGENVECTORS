# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import numpy as np
### Step 2: Assign the array values 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the values
### Step 5: End the program

## Program:
```
#Program to find the Eigen values and Eigen vectors.
#Developed by: Evangelin.S
#RegisterNumber: 21500561
import numpy as np
a=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors)
```


## Output:![eigen values vectors output](https://user-images.githubusercontent.com/94219798/144704350-540b5a13-e556-439c-8058-8b08b85af724.PNG)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
