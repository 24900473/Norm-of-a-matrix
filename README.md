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
```python
# Register No:212224230216
# Developed By: RAGAVAN

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
![Screenshot 2025-04-27 121439](https://github.com/user-attachments/assets/3feef986-6f91-4b11-ae3b-853ae7358f59)



### 2-Norm of a Matrix

![Screenshot 2025-04-27 121454](https://github.com/user-attachments/assets/ac67d1a8-5ec0-48ce-b5b3-da4b43679a61)

### Infinity Norm of a Matrix

![Screenshot 2025-04-27 121507](https://github.com/user-attachments/assets/193b7763-e6ad-448a-a065-077d28efb509)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
