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
# Program to find the solution for the given linear equations.
# Developed by: ARUNMOZHI VARMAN T
# RegisterNumber: 23002304
import numpy as np
A = np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
B = np.array([-9,4,-1])
le= np.linalg.solve(A,B)
print(le)

## Output:
![Screenshot 2024-01-02 223508](https://github.com/ArunmozhiVarmanT/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/144870523/1a54308b-bd34-4cb3-9a97-f231890606d2)

## Result:

Thus the solutions for the linear equations are successfully solved using python program

