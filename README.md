# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. Import the necessary libraries(numpy,scipy.linalg)
3. Define the matrix using numpy
4. Use lu(),lu_solve(),lu_factor() to get the solutions
5. End the program
 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Gokulan S
RegisterNumber:212225230078
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Gokulann S
RegisterNumber:212225230078
import numpy as np
from scipy.linalg import lu_factor, lu_solve
A = np.array(eval(input()))
b = np.array(eval(input()))
lu, piv = lu_factor(A)
X = lu_solve((lu , piv),b)
print(X)
*/
```

## Output:
![WhatsApp Image 2026-03-23 at 3 25 40 PM](https://github.com/user-attachments/assets/f0253c44-b9c2-41e2-bb53-52788d22a172)
![WhatsApp Image 2026-03-23 at 3 25 59 PM](https://github.com/user-attachments/assets/f42dcea7-89fe-408a-acdc-d4e6c5464b4b)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

