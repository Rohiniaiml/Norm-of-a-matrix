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
# Register No:
# Developed By:
# 1-Norm of a Matrix
import numpy as np 
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix
import numpy as np 

import numpy as np 
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix
import numpy as np 

import numpy as np 
matrix=np.array(eval(input()))
ans=np.linalg.norm(matrix,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-13 234906](https://github.com/user-attachments/assets/4d33c147-195b-4089-8dd5-b72f87b6f9a1)

### 2-Norm of a Matrix
![Screenshot 2024-12-13 234947](https://github.com/user-attachments/assets/3b7bc44e-8be0-4ea1-8f06-06b11ae01f16)


### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/610669f7-849d-4529-945b-a45ac3034168)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
