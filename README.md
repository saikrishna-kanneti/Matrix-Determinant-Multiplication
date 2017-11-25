# Matrix-Determinant-Multiplication

Numpy has in-built universal functions that allow operations on multidimentional arrays.
For this problem, we will be testing the performance of some of these functions.
For this, create an NxN matrix A and an array B of size N, with random entries (use numpy.random). 
Using A and B as inputs, performing the following operations: 
(compare and time the performance of sorting algorithms with and without numpy ufunc)
1.Sorting B (you can use numpy.sort) for N ranging from 1000 to 25000 (take steps of 1000)
2.Computing Determinant of A ( you can use numpy.linalg.det to compute the determinant of the matrix) 

3.Matrix Multiplication of A*A ( use numpy.matmul) for N ranging from 100 to 1500

Plot the operation times for Numpy functions vs regular python commands for each operation
