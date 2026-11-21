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
# Register No: 212224240163
# Developed By: Subhash V

# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix

<img width="597" height="182" alt="image" src="https://github.com/user-attachments/assets/8e8a868a-0d84-4332-9b88-68ff94c61166" />


### 2-Norm of a Matrix

<img width="667" height="207" alt="image" src="https://github.com/user-attachments/assets/b7fcbe27-7f3c-4ed0-ba27-08d011a5c5db" />


### Infinity Norm of a Matrix

<img width="702" height="173" alt="image" src="https://github.com/user-attachments/assets/65e3067a-cd9f-4e57-95fa-d86fdf44da35" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
