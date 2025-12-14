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

Program to find the L and U matrix.

Developed by: THANZIL HUSSAIN A

RegisterNumber: 25018773

```py
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
p,l,u=lu(a)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix

Program to find the LU Decomposition of a matrix.

Developed by: THANZIL HUSSAIN A

RegisterNumber: 25018773

```py
import numpy as np
from scipy.linalg import lu
a=np.array(eval(input()))
b=np.array(eval(input())) 
p,l,u=lu(a)
pb=np.dot(p.T,b)
y=np.linalg.solve(l,pb)
x=np.linalg.solve(u,y)
print(x)
```

## Output:

<img width="1007" height="605" alt="image" src="https://github.com/user-attachments/assets/e5be4445-10a3-4862-a240-12ba70ec4179" />

<img width="1107" height="617" alt="image" src="https://github.com/user-attachments/assets/a09a773c-b60e-4367-854e-07403c7a9a6a" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

