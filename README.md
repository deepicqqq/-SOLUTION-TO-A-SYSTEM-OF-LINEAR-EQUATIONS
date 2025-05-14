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

import numpy as np\
A = np.array([[2, 3],\
              [1, 2]])\
B = np.array([8, 5])\
X = np.linalg.solve(A, B)\
print("Solution of the system of equations:", X)

## Output:
![image](https://github.com/user-attachments/assets/c79d3e6f-1783-4c2c-bd51-81ace6ed9efd)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

