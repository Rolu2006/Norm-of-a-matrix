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
# Register No: Somalaraju Rohini
# Developed By:212224240156
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)






```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>





![Screenshot 2025-05-13 181952](https://github.com/user-attachments/assets/7c9e8ed9-e3ed-4238-939c-07329a8979bf)




### 2-Norm of a Matrix
<br>
<br>
<br>

![Screenshot 2025-05-13 182036](https://github.com/user-attachments/assets/962236d3-870b-449d-9da4-a480e3ea19c9)








### Infinity Norm of a Matrix
<br>
<br>
<br>





![Screenshot 2025-05-13 182119](https://github.com/user-attachments/assets/bed489f2-f31c-4e75-b228-87b513e5e28b)




## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
