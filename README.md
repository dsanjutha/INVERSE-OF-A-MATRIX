# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the NumPy module to use built-in mathematical functions.
### Step 2: 
Create lists from the coefficients of the linear equations and constants, and assign them using np.array().
### Step 3: 
Use the function np.linalg.solve() to find the solution of the given equations.
### Step 4: 
Display the result and end the program.

## Program:
```python
#Program to find the inverse of a matrix.
#Developed by:D.sanjutha 
#RegisterNumber:212225240136
import numpy as np
a=[[2,1,1],[1,1,1],[1,-1,2]]
inverse=np.linalg.inv(a)
print(inverse)
```
## Output:
<img width="1241" height="790" alt="Screenshot 2026-01-31 135320" src="https://github.com/user-attachments/assets/b94ddc5c-a455-477c-a0ea-e26ea548747c" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

