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
# Register No: 212225240052
# Developed By: a.Infant Vijay
# 1-Norm of a Matrix
import numpy as np
mat=eval(input())
one_mat=np.linalg.norm(mat,1)
print("{:.2f}".format(one_mat))




# 2-Norm of a Matrix
import numpy as np
mat=eval(input())
two_mat=np.linalg.norm(mat,2)
print("{:.2f}".format(two_mat))




# Infinity Norm of a Matrix
import numpy as np
mat=eval(input())
inf_mat=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(inf_mat))




```
## Output:
### 1-Norm of a Matrix
<br>
c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot (119).png
<br>
<br>

### 2-Norm of a Matrix
<br>
c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot (120).png
<br>
<br>

### Infinity Norm of a Matrix
<br>
c:\Users\acer\OneDrive\Pictures\Screenshots\Screenshot (121).png
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
