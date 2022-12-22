# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: import numpy package
## Step 2: get the imput matrix
## Step 3: find the rank of the matrix
## Step 4: print the result
 
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: Rakesh J.S
#RegisterNumber:22009339
import numpy as np
A = np.array([[3,2,5],[1,1,2],[3,3,6]])
B=np.linalg.matrix_rank(A)
values,vectors = np.linalg.eig(A)
print(B)
```
## Output:
![](/rank.png)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

