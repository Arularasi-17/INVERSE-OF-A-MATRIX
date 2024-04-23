# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Calculate the determinant of the matrix. If the determinant is zero, then the matrix is singular and doesn't have an inverse. 
### Step 2: 
If the determinant is non-zero, calculate the adjoint of the matrix. The adjoint of a matrix is the transpose of the cofactor matrix.
### Step 3:
Scale the adjoint matrix by dividing each element by the determinant of the original matrix. 
### Step 4: 
The scaled adjoint matrix is the inverse of the original matrix.

## Program:
#Program to find the inverse of a matrix.\
#Developed by:ARULARASI U \
#RegisterNumber:212223100002\
import numpy as np\
matrix=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])\
result=np.linalg.inv(matrix)\
print(result)
## Output:
![alt text](<Screenshot 2024-04-23 110305.png>)
![alt text](<Screenshot 2024-04-23 110253.png>)

## Result:
Thus the inverse of given matrix is successfully solved using python program

