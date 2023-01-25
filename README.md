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
# Register No: ATHMAJ VENUGOPAL
# Developed By: 22007603

# 1-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

import numpy as np

mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


```
## Output:
### 1-Norm of a Matrix
![norm1](https://user-images.githubusercontent.com/118753139/214638087-4a4aca5e-7cfa-4c2d-9868-253f30419d23.png)


### 2-Norm of a Matrix
![norm2](https://user-images.githubusercontent.com/118753139/214638183-cfff0bc1-bc15-4b6e-9efc-44a004b6ac49.png)


### Infinity Norm of a Matrix
![norm3](https://user-images.githubusercontent.com/118753139/214638202-07d4ab2b-9b05-433c-8e21-1a27727ea229.png)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
