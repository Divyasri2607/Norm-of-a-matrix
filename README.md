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
```
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)
```
```
'''
Program to find 2-norm of a matrix.
Developed by: Divya Sri V
RegisterNumber: 212224230070
'''

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print("{:.2f}".format(result))
```
```
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(result))
```
## Output:
![image](https://github.com/user-attachments/assets/6ec31e46-2db6-4ab8-9266-6282b43ee5b1)
![image](https://github.com/user-attachments/assets/11a6d35f-9714-46f3-9bad-1a69b0cef37a)
![image](https://github.com/user-attachments/assets/e1d7a0c5-70fd-4c1a-943d-7c51bbace23d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
