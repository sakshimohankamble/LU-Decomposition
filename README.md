# LU-Decomposition
LU-Decomposition or lower-upper (LU) decomposition is a matrix as the product of a lower triangular matrix and an upper triangular matrix. The product sometimes includes a permutation matrix as well. LU decomposition can be viewed as the matrix form of Gaussian elimination.

**The LU decomposition of a matrix A is the pair of matrices L and U such that:**

• A = LU
• L is a lower-triangular matrix with all diagonal entries equal to 1
• U is an upper-triangular matrix

**Ex:**
AX=B , where A=LU.
    LUX=B, let Y=UX.
    LY=B.
We have to find values of X.

1) Compile and create one executable file using command(" gcc LUDecomposition.c -o output ")
2) Run the executable file "output" by using(" ./output ")
3) First input the order of matrix A.
4) Then input all the elements of matrix A one by one.
5) Input all the elements of vector B.
6) At last the output containing L, U, Y, X will be visible on screen.
