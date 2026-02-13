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
# Register No: 212224240141
# Developed By: Sai Ram E

# 1-Norm of a Matrix
'''

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2) 
norm_of_matrix="{:.2f}".format(ans)
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
<img width="1226" height="834" alt="image" src="https://github.com/user-attachments/assets/cbf0acf0-0dba-4bec-af54-691b9dead2d0" />
<img width="1227" height="341" alt="image" src="https://github.com/user-attachments/assets/bd220427-9d4c-457a-bb72-2988dff9afc2" />


### 2-Norm of a Matrix
<img width="1225" height="880" alt="image" src="https://github.com/user-attachments/assets/612c7f20-3dfa-4819-88d6-8beab2d96535" />
<img width="1232" height="389" alt="image" src="https://github.com/user-attachments/assets/f7281950-da5c-42f8-bb22-a145b69e62d7" />


### Infinity Norm of a Matrix
<img width="1229" height="797" alt="image" src="https://github.com/user-attachments/assets/ad0503d7-9e23-4c0b-b8d5-90c24939358c" />
<img width="1232" height="341" alt="image" src="https://github.com/user-attachments/assets/7e150cfa-df1d-48c7-85bc-c1c4cb782403" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
