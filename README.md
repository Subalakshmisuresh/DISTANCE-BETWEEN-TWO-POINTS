# DISTANCE-BETWEEN-TWO-POINTS

## AIM:
To write a python program to find the distance two 2 points
## ALGORITHM:
### Step 1: 
Import numpy module to use built-in functions
### Step 2: 
Get lists from the linear equations and assign it to np.array
### Step 3: 
Substitute the values in the distance formula  ![formula](/formula.JPG)
### Step 4: 
Print the result.
### Step 5: 
End the program.
### PROGRAM:
  ```
#Program to find the eigen values and eigen vectors.

#Developed by: SUBALAKSHMI.S

#RegisterNumber: 212222100051

import numpy as np

A = np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```


### OUTPUT:

![image](https://github.com/Subalakshmisuresh/DISTANCE-BETWEEN-TWO-POINTS/assets/121957896/a0640571-4052-4856-a604-8005070274a0)


### RESULT:

Thus the distance between the two points is successfully obtained.
