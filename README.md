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
# 1-Norm of a Matrix
```python
Program to find 1-norm of a matrix.
Developed by:vignesh.v
RegisterNumber:23004027

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```


# 2-Norm of a Matrix
```python



```
# Infinity Norm of a Matrix





```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-29 214115](https://github.com/23004027/Norm-of-a-matrix/assets/138956447/8965073c-dda7-458b-a6c7-5b6f4d8be182)


### 2-Norm of a Matrix
![Screenshot 2023-12-29 214130](https://github.com/23004027/Norm-of-a-matrix/assets/138956447/3fe26b4f-a4ae-41db-94e3-4045eb9eb02e)


### 3-Infinity Norm of a Matrix
![Screenshot 2023-12-29 214216](https://github.com/23004027/Norm-of-a-matrix/assets/138956447/d1508634-d7cc-40ae-8e3f-0b206728533d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
