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
# Register No: 212222230131
# Developed By:Sanjay G
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix= "{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat= np.array(eval(input()))
ans= np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/Sanjay-sg/Norm-of-a-matrix/assets/119559022/d678939d-d06b-4b37-a9fe-31887df3859a)

### 2-Norm of a Matrix
![image](https://github.com/Sanjay-sg/Norm-of-a-matrix/assets/119559022/471b6e36-b4e6-416d-b7f1-2defae8d2514)

### Infinity Norm of a Matrix
![image](https://github.com/Sanjay-sg/Norm-of-a-matrix/assets/119559022/f80e368b-db85-4398-819f-9fba7ee623ed)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
