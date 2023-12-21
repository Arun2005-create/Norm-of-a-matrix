# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python

# 1-Norm of a Matrix
'''
Program to find the 1-Norm of a matrix
#Developed by: Arun Kumar B
#Register Number: 23004514
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print('{:.2f}'.format(norm))



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: Arun Kumar B
RegisterNumber: 23004514
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print('{:.2f}'.format(norm))



# Infinity Norm of a Matrix
'''
Program to find the infinity of a matrix.
Developed by: Arun Kumar B
RegisterNumber: 23004514
'''
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print('{:.2f}'.format(norm))





```
## Output:
### 1-Norm of a Matrix
![norm1](https://github.com/Arun2005-create/Norm-of-a-matrix/assets/138849356/680362f8-8341-4b39-922d-f03b6ae090e3)


### 2-Norm of a Matrix
![norm2](https://github.com/Arun2005-create/Norm-of-a-matrix/assets/138849356/3ad23153-3a80-47f0-9bfd-573e21eda643)


### Infinity Norm of a Matrix
![norm3](https://github.com/Arun2005-create/Norm-of-a-matrix/assets/138849356/2d9ef02e-8a38-46ef-9238-c6740c9fea1a)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
