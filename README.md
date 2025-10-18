# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Start the program.

2. Import numpy as `sp` to perform matrix operations.

3. Get the input matrix A from the user or define it in the program.

4. Use the LU decomposition function from NumPy (`sp.linalg.lu` or `scipy.linalg.lu`) to find the Lower (`L`) and Upper (`U`) matrices.

5. Store the results of decomposition in variables `l` and `u`.

6. Print the L matrix (Lower triangular matrix).

7. Print the U matrix (Upper triangular matrix).

8. End the program.

---



## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: DILLI PRATHAP.D
RegisterNumber: 212224110014
*/

import numpy as sp
from scipy.linalg import lu
s=sp.array(eval(input()))
p,l,u=lu(s)
print(l)
print(u)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: DILLI PRATHAP.D
RegisterNumber: 212224110014
*/
# To print X matrix (solution to the equations)
import numpy as sp
d=sp.array(eval(input()))
lu,piv=lu_factor(s)
x=lu_solve((lu,piv),d)
print(x)
```

## Output:
![lu decomposition]()

<img width="1920" height="1140" alt="Screenshot 2025-10-18 160706" src="https://github.com/user-attachments/assets/47ad6cbb-2c87-490c-aee2-9bab6834ce92" />

<img width="1920" height="1140" alt="Screenshot 2025-10-18 160640" src="https://github.com/user-attachments/assets/90536df6-8d12-4f10-a626-f79d31255908" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

