# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program and read the square matrix A.
### Step 2: 
Find the determinant of the matrix. If det(A)=0, the inverse does not exist.
### Step 3:
Find the inverse using the formula

A
−1
=
∣A∣
1
	​

adj(A)

where ∣A∣ is the determinant and adj(A) is the adjoint matrix.
### Step 4:
Display the inverse matrix A
−1
 and stop.

## Program:
~~~
#Program to find the inverse of a matrix.
#Developed by: SIVA SUNDAR P
#RegisterNumber: 212225040416
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[2,1,1],[1,1,1],[1,-1,2]])
b=np.linalg.inv(a)
print(b)
~~~
## Output:
<img width="895" height="324" alt="Screenshot 2026-08-18 223744" src="https://github.com/user-attachments/assets/6954c222-71e2-49dc-83c5-e68cebaf66d0" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

