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
# Register No:212224220042
# Developed By:jayagar.T
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np


mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix=f"{ans:.2f}"
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/25f63ce2-e8c2-4f0b-bd99-5fbde7ad917e)


### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/e2aef971-7339-4b10-89c3-275143355f1c)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/ab4172a0-2ced-4e2a-9833-57461775d486)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
