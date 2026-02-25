# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program

## Program:
```
import numpy as np
a=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
x=np.linalg.inv(a)
print(x)
```

## Output:
<img width="1659" height="971" alt="Screenshot 2026-02-25 140500" src="https://github.com/user-attachments/assets/59c69ceb-9c46-46b7-b204-fe1d6eeca14b" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

