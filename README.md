# Norm of a matrix
## NAME: Jayagar.T
## REG.NO: 212224220042
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
(i)
1. Import NumPy library for matrix operations.

2. Read the input matrix from the user:
   - Use eval(input()) to read the matrix as a list of lists.
   - Convert the input list into a NumPy array.

3. Calculate the 1-norm of the matrix:
   - Use np.linalg.norm() with ord=1 to compute the maximum absolute column sum.

4. Format the calculated norm to two decimal places.

5. Print the formatted norm value.
   (ii)

   1. Import the NumPy library for numerical computations.

2. Read the input matrix from the user:
   - Use eval(input()) to input the matrix as a list of lists.
   - Convert the list into a NumPy array.

3. Calculate the 2-norm of the matrix:
   - Use np.linalg.norm() with ord=2 to compute the spectral norm.

4. Format the computed norm to two decimal places.

5. Print the formatted norm value.
(iii)
1. Import the NumPy library for numerical operations.

2. Read the input matrix from the user:
   - Use eval(input()) to accept the matrix as a list of lists.
   - Convert the list into a NumPy array.

3. Calculate the infinity norm of the matrix:
   - Use np.linalg.norm() with ord=np.inf to compute the maximum absolute row sum.

4. Format the calculated norm to two decimal places.

5. Print the formatted norm value.

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
