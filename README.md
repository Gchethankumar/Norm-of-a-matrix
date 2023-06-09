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
Register No: 212222240022
Developed By: G.Chethan kumar

# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix

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


![Screenshot 2023-06-09 191939](https://github.com/Gchethankumar/Norm-of-a-matrix/assets/118348224/a9b3e021-9aa3-473e-8477-138446d49df2)


### 2-Norm of a Matrix

![Screenshot 2023-06-09 191953](https://github.com/Gchethankumar/Norm-of-a-matrix/assets/118348224/329356b9-ffbb-46d0-bd67-5566abca3a10)



### Infinity Norm of a Matrix

![Screenshot 2023-06-09 192006](https://github.com/Gchethankumar/Norm-of-a-matrix/assets/118348224/1aa3b4e4-7121-4c45-8575-07d02fe2a0a9)


## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
