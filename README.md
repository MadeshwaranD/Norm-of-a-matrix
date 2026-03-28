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
# Register No: 212225040212
# Developed By: Madeshwaran D
# 1-Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")

# 2-Norm of a Matrix
import numpy as np

# Type your code here
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")


# Infinity Norm of a Matrix

import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")



```
## Output:
### 1-Norm of a Matrix
<img width="1203" height="300" alt="image" src="https://github.com/user-attachments/assets/8feb67cc-db09-40f4-8407-82811e26d380" />

### 2-Norm of a Matrix
<img width="1207" height="341" alt="image" src="https://github.com/user-attachments/assets/9f808a7d-ea9b-4bce-b4f3-52097180ecce" />


### Infinity Norm of a Matrix
<img width="1202" height="298" alt="image" src="https://github.com/user-attachments/assets/81c23f0c-fae9-4ee6-b645-aa1e272476d2" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
