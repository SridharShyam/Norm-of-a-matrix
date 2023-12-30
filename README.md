# Norm of a matrix
### NAME: SHYAM S
### REG.NO: 23012478
### DEPT: AIML
## Aim:
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
# Developed By: SHYAM S
# Register No: 23012478
# 1-Norm of a Matrix:

import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix:

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-30 132226](https://github.com/SridharShyam/Norm-of-a-matrix/assets/144871368/846c34e6-98c8-4cf9-8414-d48e20970b7f)


### 2-Norm of a Matrix
![Screenshot 2023-12-30 132253](https://github.com/SridharShyam/Norm-of-a-matrix/assets/144871368/b2adb1b4-0c1c-4bbb-8c8a-feb77cc3e397)


### Infinity Norm of a Matrix
![Screenshot 2023-12-30 132324](https://github.com/SridharShyam/Norm-of-a-matrix/assets/144871368/3488d349-8ef0-4ccb-9f64-80db8c324a0b)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
