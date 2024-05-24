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
```
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: K.Deekshitha
RegisterNumber:2305002005
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)




# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: K.Deekshitha
RegisterNumber:2305002005
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix

'''
Program to find infinity-norm of a matrix.
Developed by: K.Deekshitha
RegisterNumber: 2305002005
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/kilarideekshi/Norm-of-a-matrix/assets/155507099/e601a383-1496-403f-b73f-c35f9a753a37)


### 2-Norm of a Matrix
![image](https://github.com/kilarideekshi/Norm-of-a-matrix/assets/155507099/03d2b48e-2394-4c12-9469-46f338484bf3)

### Infinity Norm of a Matrix
![image](https://github.com/kilarideekshi/Norm-of-a-matrix/assets/155507099/d5c92728-2a30-4a21-adcb-1066c5fec73a)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
