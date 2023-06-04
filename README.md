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
# Register No:yogesh rao S D
# Developed By:212222110055

# 1-Norm of a Matrix
import numpy as np
mat =np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix

![ex-7(1)](https://github.com/yogeshrao05/Norm-of-a-matrix/assets/122008288/d3753b51-bb4e-49bb-ad4f-e025f708b44c)

### 2-Norm of a Matrix

![ex-7(2)](https://github.com/yogeshrao05/Norm-of-a-matrix/assets/122008288/a3f89175-7fd4-4f41-861f-da996022d99f)

### Infinity Norm of a Matrix

![ex 07](https://github.com/yogeshrao05/Norm-of-a-matrix/assets/122008288/c52dd3d8-1bf1-4d9a-b4f1-68264a9043f8)

## Result:
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
