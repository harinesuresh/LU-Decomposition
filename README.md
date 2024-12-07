# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import the numpy and scipy module to use the built-in functions for calculation
2. Prepare the lists for the given matrix and assign in np.array()
3. Using the scipy.linalg.lu(), we get L and U of the given matrix. Using the scipy.linalg.lu_factor()
and scipy.linalg.lu_solve we get the LU decomposition of the given matrix.
4. End of the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Harine S
RegisterNumber: 24900210
*/
```
    import numpy as np
    from scipy.linalg import lu
    A=np.array(eval(input()))
    P,L,U=lu(A)
    print(L)
    print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Harine S
RegisterNumber: 24900210
*/
```
    import numpy as np
    from scipy.linalg import lu_factor,lu_solve
    AMatrix=np.array(eval(input()),dtype='i')
    BMatrix=np.array(eval(input()),dtype='i')
    XMatrix=lu_factor(AMatrix)
    solution=lu_solve(XMatrix,BMatrix)
    print(solution)

## Output:
![lu decomposition]
![alt text](<Screenshot (10)-1.jpg>)
![alt text](<Screenshot (11)-1.jpg>)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

