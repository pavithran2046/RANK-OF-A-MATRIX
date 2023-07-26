# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import munpy module to use the built in functions for calculation
### Step 2: 
prepare the list form ecah linear equation andassing in np.array()
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
end the programe 
## Program:
``` python
#Program to find the rank of a matrix.
#Developed by: pavithran S
#RegisterNumber:23001643
import numpy as np
a=[[5,-3,-10],[2,2,-3],[-3,-1,5]]
b=np.array(a)
print(np.linalg.matrix_rank(b))
```
## Output:
![output](/Screenshot%202023-07-26%20174805.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

