# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print' .

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X 
 ## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: 
RegisterNumber:
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,l,u=lu(A)
print(l)
print(u)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: 
RegisterNumber:
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
Lu,piv=lu_factor(A)
s=lu_solve((Lu,piv),b)
print(s) 
*/
```

## Output:
![Screenshot 2024-12-06 144847](https://github.com/user-attachments/assets/18a13030-f4a3-4c89-98d6-9a51300d8d9d)
![Screenshot 2024-12-06 144450](https://github.com/user-attachments/assets/4368be03-5d8d-455e-ae48-509d59ebbde3)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

