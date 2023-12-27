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
# 1-Norm of a Matrix
```
Program to find 1-norm of a matrix.
Developed by: HENRIPRASATH.S
RegisterNumber: 23003595
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print("{:.2f}".format(norm))
```

# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: HENRIPRASATH.S
RegisterNumber: 23003595
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))
```

# Infinity Norm of a Matrix
```
Program to find the infinity of a matrix.
Developed by: HENRIPRASATH.S
RegisterNumber: 23003595
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print("{:.2f}".format(norm))
```

## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-27 232734](https://github.com/Henriprasath/Norm-of-a-matrix/assets/144979077/7034999a-a4a9-45ea-9771-e2781746cf36)



### 2-Norm of a Matrix
![Screenshot 2023-12-27 232748](https://github.com/Henriprasath/Norm-of-a-matrix/assets/144979077/3b22f9d0-39c5-4d49-9309-69b8f1a469c2)


### Infinity Norm of a Matrix
![Screenshot 2023-12-27 232802](https://github.com/Henriprasath/Norm-of-a-matrix/assets/144979077/6a4d7c72-4fed-4909-939d-390f408854c3)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
