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
```import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```



# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: yourname:RITHIKA.N
RegisterNumber: 23013374
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```



# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```




```
## Output:
### 1-Norm of a Matrix
<br>
<br>![Screenshot 2023-12-26 103422](https://github.com/Rithikachezhian/Norm-of-a-matrix/assets/145742406/d402d6fb-04f6-42c3-bc15-f0e5e1823f2d)

<br>

### 2-Norm of a Matrix
<br>
<br>![Screenshot 2023-12-26 103434](https://github.com/Rithikachezhian/Norm-of-a-matrix/assets/145742406/399793cd-e409-46f4-883b-72be2be56e7c)

<br>

### Infinity Norm of a Matrix
<br>
<br>![Screenshot 2023-12-26 103447](https://github.com/Rithikachezhian/Norm-of-a-matrix/assets/145742406/5122e6f9-93d9-4431-87ca-755293330fc9)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
