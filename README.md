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

![Screenshot 2023-04-29 212218](https://user-images.githubusercontent.com/118348224/235311760-8a80cf9e-955e-4d54-bd1d-097d27e398cc.png)


### 2-Norm of a Matrix

![Screenshot 2023-04-29 212230](https://user-images.githubusercontent.com/118348224/235311763-501a256c-0151-4221-9df4-3771ef252ba1.png)


### Infinity Norm of a Matrix

![Screenshot 2023-04-29 212244](https://user-images.githubusercontent.com/118348224/235311765-7e6abadb-6b01-4198-99d2-239ba75ab388.png)


## Result

Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
