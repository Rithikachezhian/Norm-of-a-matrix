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
# Register No:rithika N
# Developed By:212223230172
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
RegisterNumber: 212223230172
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

![Screenshot 2024-04-23 115429](https://github.com/Rithikachezhian/Norm-of-a-matrix/assets/145742406/c9f4cd15-8af3-4ba2-b583-41c12de47b39)

### 2-Norm of a Matrix

![Screenshot 2024-04-23 115443](https://github.com/Rithikachezhian/Norm-of-a-matrix/assets/145742406/3cc4044d-5e4f-40b3-8a06-2f7b44d87913)

### Infinity Norm of a Matrix

![Screenshot 2024-04-23 115457](https://github.com/Rithikachezhian/Norm-of-a-matrix/assets/145742406/d436a9a6-cd69-4438-a479-5f8360e11091)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
