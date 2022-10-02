# 2-Norm of a matrix
## Aim
To write a program to find the 2-norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1. Get the input matrix using np.array()
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.   
## Program:
```python
'''
Program to find 2-norm of a matrix.
Developed by: yuvabharathib
RegisterNumber: 22002787
'''

import numpy as np
arr=np.array(eval(input()))
n=np.linalg.norm(arr,2)
print("{:.2f}".format(n))
```
## Output:
![2 norm of a matrix](https://user-images.githubusercontent.com/113497406/192082084-5f0fe60d-7eb9-486e-86df-f6739922554e.png)

## Result
Thus the program for 2-norm of a matrix is written and verified.
