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
```
# Register No: 212225100061
# Developed By: Yogesh G
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
<img width="810" height="693" alt="Screenshot 2026-06-01 142101" src="https://github.com/user-attachments/assets/ef8d5bfe-5faa-40c0-b6b6-254722479b8e" />


### 2-Norm of a Matrix
<img width="564" height="719" alt="Screenshot 2026-06-01 142109" src="https://github.com/user-attachments/assets/383bf05f-dc39-44bb-bf35-6af3381201a4" />


### Infinity Norm of a Matrix
<img width="661" height="596" alt="Screenshot 2026-06-01 142117" src="https://github.com/user-attachments/assets/4d633b0f-e8eb-4cf4-bdba-186ac6673855" />



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
