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
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))




# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr = np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))





```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![image](https://github.com/nainamohamed09642/Norm-of-a-matrix/assets/151916360/f5a43f87-4127-437f-bf84-b13b03e46617)


### 2-Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2023-12-29 114332](https://github.com/nainamohamed09642/Norm-of-a-matrix/assets/151916360/5b3088c7-df07-421d-bd7d-546687344038)


### Infinity Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2023-12-29 114304](https://github.com/nainamohamed09642/Norm-of-a-matrix/assets/151916360/052da664-024e-46e9-9b44-e572116c4bcf)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
