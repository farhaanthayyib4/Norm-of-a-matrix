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
# Register No: 212225230069
# Developed By: FARHAAN THAYYIB L
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array(eval(input()))

norm = np.linalg.norm(a, 1)

print("%.2f" % norm)



# 2-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array(eval(input()))

norm = np.linalg.norm(a, 2)

print("%.2f" % norm)



# Infinity Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a = np.array(eval(input()))

norm = np.linalg.norm(a, np.inf)

print("%.2f" % norm)




```
## Output:
<img width="981" height="693" alt="image" src="https://github.com/user-attachments/assets/1467280e-085e-474a-9bcd-416ea9a4ddb9" />
<img width="996" height="789" alt="image" src="https://github.com/user-attachments/assets/53bac390-0a1a-4350-a9e7-4189d0ad8f03" />
<img width="1157" height="718" alt="image" src="https://github.com/user-attachments/assets/f8f30bb0-c149-4d9c-a8e3-4cbd30ddb4f5" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
