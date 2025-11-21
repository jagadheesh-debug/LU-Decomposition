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
Developed by: MOHAMED ASARUDEEN A
RegisterNumber: 25005844
*/
import numpy as np
from scipy.linalg import lu
InputMatrix=np.array(eval(input()),dtype='i')
piv,Lmatrix,Umatrix=lu(InputMatrix)
print(Lmatrix)
print(Umatrix)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: MOHAMED ASARUDEEN A
RegisterNumber: 25005844
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
Solution=lu_solve(XMatrix,BMatrix)
print(Solution)
```

## Output:
![lu decomposition]()
<img width="905" height="942" alt="Screenshot 2025-11-21 204712" src="https://github.com/user-attachments/assets/1393c75a-2ae2-41f7-aaff-6b79b17e5f4a" />
<img width="1312" height="902" alt="Screenshot 2025-11-21 204643" src="https://github.com/user-attachments/assets/7e027d4d-df43-441a-813a-48cbf43fa8bf" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

