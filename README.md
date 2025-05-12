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
import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,1)
print(result)



# 2-Norm of a Matrix
import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,2)
print("{:.2f}".format(result))



# Infinity Norm of a Matrix

import numpy as np
matrix = np.array(eval(input()))
result = np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/014f770d-5392-4281-8483-923e0cf9c31c)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/4cafe0b0-f7f0-44e6-9e14-415082366efc)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/bd0eb287-a84d-4023-b74b-8886ae2d8d08)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
