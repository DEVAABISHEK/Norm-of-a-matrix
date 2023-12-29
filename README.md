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

# 1-Norm of a Matrix
#Program to find the 1-Norm of a matrix
#Developed by: DEVA ABISHEK P
#RegisterNumber: 23012976
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm="{:.2f}".format(ans)
print(norm)



# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: DEVA ABISHEK P
RegisterNumber: 23012976
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm="{:.2f}".format(ans)
print(norm)



# Infinity Norm of a Matrix
'''
Program to find the Infinity of a matrix 
Developed by: DEVA ABISHEK P
RegisterNumber: 23012976
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm="{:.2f}".format(ans)
print(norm)




```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/DEVAABISHEK/Norm-of-a-matrix/assets/150319305/2576b3b7-519c-44be-ae4b-4930b6e62aae)

### 2-Norm of a Matrix
![image](https://github.com/DEVAABISHEK/Norm-of-a-matrix/assets/150319305/32899c96-5540-464f-9d46-e7b3df444b08)


### Infinity Norm of a Matrix
![image](https://github.com/DEVAABISHEK/Norm-of-a-matrix/assets/150319305/e04efa6f-c8dc-4a2a-a86b-0157d1c365c4)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
