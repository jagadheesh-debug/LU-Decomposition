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
Developed by: Jagadheesh kumar T
RegisterNumber: 212225040139
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
Developed by: Jagadheesh kumar T
RegisterNumber: 212225040139
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

<img width="1272" height="792" alt="Screenshot 2026-05-21 113631" src="https://github.com/user-attachments/assets/66a3b904-656f-4373-85c5-aceb6fc745b6" />
<img width="1357" height="607" alt="Screenshot 2026-05-21 113710" src="https://github.com/user-attachments/assets/34dc3776-a52d-48bf-a904-16f62d1f6871" />
<img width="1382" height="786" alt="Screenshot 2026-05-21 113657" src="https://github.com/user-attachments/assets/c8bdeabf-8ca8-4ca2-851d-9ef49e72b373" />
<img width="1345" height="420" alt="Screenshot 2026-05-21 113721" src="https://github.com/user-attachments/assets/5e8f83b8-856b-4c98-bc57-622fef1a5f8a" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

