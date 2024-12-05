# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. 
2. 
3. 
4. 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: ARSHATH HUSSAIN I
RegisterNumber: 24008800
*/
```
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: ARSHATH HUSSAIN I
RegisterNumber: 24008800
*/
```
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu,lu_solve,lu_factor
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)


## Output:
![Screenshot 2024-12-05 231244](https://github.com/user-attachments/assets/5401e0ec-d40d-4c90-95b4-da73fd0e9bcb)
![Screenshot 2024-12-05 231300](https://github.com/user-attachments/assets/7f799041-2142-4014-8507-816c81a81737)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

