# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## DATE:
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
```
#Program to find the solution for the given linear equations.
#Developed by: G Leka Sri
#RegisterNumber: 212223100025
import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
c=np.linalg.solve(a,b)
print(c)
```

## Output:
![Screenshot 2024-09-04 155126](https://github.com/user-attachments/assets/ad319c19-3010-4b6e-bc7c-ee26c8a100c9)


## Result: 
Thus the solutions for the linear equations are successfully solved using python program

