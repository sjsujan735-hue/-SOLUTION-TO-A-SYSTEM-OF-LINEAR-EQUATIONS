# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:
#Program to find the solution for the given linear equations.
#Developed by: Sujan S
#RegisterNumber:212225220108
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
X=np.linalg.solve(A,B)
print(X)
## Output:
<img width="1438" height="847" alt="Screenshot 2026-05-14 103941" src="https://github.com/user-attachments/assets/e1ceac9f-014b-432b-bf38-8a1997df00b6" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

