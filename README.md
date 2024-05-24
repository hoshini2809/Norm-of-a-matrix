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
# Register No:2305003006
# Developed By: Hoshini S
# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# 2-Norm of a Matrix
# Register No:2305003006
# Developed By: Hoshini S
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
# Register No:2305003006
# Developed By: Hoshini S
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,np.inf)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-05-24 194527](https://github.com/hoshini2809/Norm-of-a-matrix/assets/170595101/1bb59eb8-2d8e-400b-b7b9-201c6e7daad7)


### 2-Norm of a Matrix
![Screenshot 2024-05-24 194631](https://github.com/hoshini2809/Norm-of-a-matrix/assets/170595101/df45768a-7dc5-455a-b6e2-91d5d6bec8e3)


### Infinity Norm of a Matrix
![Screenshot 2024-05-24 194733](https://github.com/hoshini2809/Norm-of-a-matrix/assets/170595101/ab504bc7-db57-4ce1-967e-7ae243e44b93)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
