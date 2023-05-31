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
'''
Program to find the 1-Norm of a matrix and display the results in two decimal places.
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




# Infinity Norm of a Matrix

'''
Program to find the Infinity of a matrix and display the result in two decimal places.
Developed by: M.CHANDRU
RegisterNumber: 212222230026
'''
import numpy as np

mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix

![Screenshot (85)](https://github.com/chandrumathiyazhagan/Norm-of-a-matrix/assets/119393023/46f51669-97c0-4a3a-99d2-bbc3c0c823d8)

<br>
<br>
<br>

### 2-Norm of a Matrix

![Screenshot (86)](https://github.com/chandrumathiyazhagan/Norm-of-a-matrix/assets/119393023/71059866-75a6-4d8b-a3f0-16f47b3dbaef)

<br>
<br>
<br>

### Infinity Norm of a Matrix

![Screenshot (87)](https://github.com/chandrumathiyazhagan/Norm-of-a-matrix/assets/119393023/2ebf8f52-551f-4bc8-935c-d1c020974737)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
