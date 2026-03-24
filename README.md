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
# Register No:212225240041
# Developed By:GINI CLARE G
# 1-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))




# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))




# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
matrix=eval(input())
inf_matrix=np.linalg.norm(matrix,np.inf)
print("{:.2f}".format(inf_matrix))




```
## Output:
### 1-Norm of a Matrix
<img width="1213" height="801" alt="Screenshot 2026-03-24 142225" src="https://github.com/user-attachments/assets/8b6b98d9-b21f-4240-8651-f2bb535e0806" />


### 2-Norm of a Matrix
<img width="1187" height="843" alt="Screenshot 2026-03-24 142250" src="https://github.com/user-attachments/assets/982248db-7884-477e-87e2-ffbe8dc39228" />

### Infinity Norm of a Matrix
<img width="950" height="754" alt="Screenshot 2026-03-24 142311" src="https://github.com/user-attachments/assets/c39380f9-74fd-426c-82a6-96c97df9c3f2" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
