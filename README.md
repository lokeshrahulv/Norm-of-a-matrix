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
# Register No:22004702
# Developed By:LOKESH RAHUL V V 
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://user-images.githubusercontent.com/118423842/213350977-b0244c15-b039-4462-ad28-a811c05785a7.png)

### 2-Norm of a Matrix
![image](https://user-images.githubusercontent.com/118423842/213351037-1e9a2aca-cdb1-412b-a726-1612f8dc45ca.png)

### Infinity Norm of a Matrix
![image](https://user-images.githubusercontent.com/118423842/213351064-b26ac91c-4ec5-4fdc-819c-37656e311459.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
