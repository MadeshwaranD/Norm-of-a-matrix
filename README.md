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
...
Python
# Register No: 212225040212
# Developed By: Madeshwaran D
# 1-Norm of a Matrix
...
...
import numpy as np
A=np.array(eval(input()))
norm1=np.linalg.norm(A,1)
print(f"{norm1:.2f}")
...


<img width="1204" height="738" alt="image" src="https://github.com/user-attachments/assets/23bb474d-1092-4ff8-b13a-3eafb82a03b1" />



# 2-Norm of a Matrix
...
import numpy as np
A=np.array(eval(input()))
norm2=np.linalg.norm(A,2)
print(f"{norm2:.2f}")
...



![WhatsApp Image 2026-03-28 at 8 39 04 AM](https://github.com/user-attachments/assets/1b90aeb9-d5a1-40a4-849e-29a5ea8d1bf0)

# Infinity Norm of a Matrix
...
import numpy as np
A=np.array(eval(input()))
norminf=np.linalg.norm(A,np.inf)
print(f"{norminf:.2f}")
...

<img width="1207" height="706" alt="image" src="https://github.com/user-attachments/assets/45f5ac60-f393-4e73-a985-4f0a35be0224" />


## Output:
### 1-Norm of a Matrix
<img width="1203" height="300" alt="image" src="https://github.com/user-attachments/assets/c671a628-da69-4424-90ed-47c958fdb30a" />

### 2-Norm of a Matrix
<img width="1207" height="341" alt="image" src="https://github.com/user-attachments/assets/4c0bcf4b-15b0-4993-bf37-232d6845df4d" />

### Infinity Norm of a Matrix
<img width="1202" height="298" alt="image" src="https://github.com/user-attachments/assets/4e5a17d2-25d7-459c-bd30-ceaf12c708ec" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
