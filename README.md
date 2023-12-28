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
```
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```


# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: pavithra.D
RegisterNumber: 23004871
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))




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

<br>![Screenshot 2023-12-28 143228](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145742406/92f0ddd8-c9de-4816-a711-8932c2b56157)

<br>

### 2-Norm of a Matrix
<br>

<br>![Screenshot 2023-12-28 143239](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145742406/5092a08f-dd83-429b-b432-ac2d20c2fb07)

<br>

### Infinity Norm of a Matrix
<br>

<br>![Screenshot 2023-12-28 143251](https://github.com/etjabajasphin/Norm-of-a-matrix/assets/145742406/ea6a97d9-523e-47e3-8f2a-0202c32a92ed)

<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
