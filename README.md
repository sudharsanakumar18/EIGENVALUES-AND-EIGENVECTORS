# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:

###Step1 : import num py
###Step 2: use an array function
###Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue andsecond is eigenvector) of the given matrix.
###Step 4: then print the eigen value

## Program:
```
import numpy as np
a=[[2,-3,0],[2,-5,0],[0,0,3]]
values,Vectors=np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are", Vectors)
```

## Output:
![image](https://raw.githubusercontent.com/sudharsanakumar18/EIGENVALUES-AND-EIGENVECTORS/main/maths%20exp%2004.png)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
