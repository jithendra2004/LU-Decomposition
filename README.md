# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement. 
2. From scipy package import lu().
3. Get input from user and pass it as an array.
4. Get P, L U martix using lu().
5. print L and U matrix.
## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:V.A.Jithendra 
RegisterNumber:21005049
*/
# To print L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

## Output:
![lu decomposition](https://github.com/jithendra2004/LU-Decomposition/blob/main/lu%20output.png?raw=true)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

# LU Decomposition without zero on the diagonal

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy library using import statement. 
2. From scipy.linalg.
3. Get input from user.
4. execute the program.
5. End the program.
## Program:
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:V.A.Jithendra
RegisterNumber:21005049
*/

import numpy as np
import scipy
from scipy.linalg import lu_factor,lu_solve
A=([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
B=([4, 5, 7])
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
```

## Output:
![lu decomposition](luoutput.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

