# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the required NumPy library using import numpy as np.
### Step 2: 
Define the matrix as a NumPy array (example: A = np.array([[2, 1, 1],[1, 1, 1],[1, -1, 2]])).
### Step 3: 
Use the built-in function np.linalg.inv(A) to compute the inverse of the matrix.
### Step 4: 
Store the result in a variable (e.g., A_inv) and display the inverse matrix using the print() function.

## Program:
~~~python
#Program to find the inverse of a matrix.
#Developed by: Harikrishnan.S
#RegisterNumber:212224100020
import numpy as np
A = np.array([[2,1,1],[1,1,1],[1,-1,2]])
AInverse = np.linalg.inv(A)
print(AInverse)
~~~

## Output:
<img width="1282" height="891" alt="image" src="https://github.com/user-attachments/assets/4444f229-e3a6-46a1-aecd-e7be667616e0" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

