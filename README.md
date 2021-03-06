# ProgrammingAssignment2

Assignment: Caching the Inverse of a Matrix

Matrix inversion is usually a costly computation and their may be some benefit to caching the inverse of a matrix rather than compute it repeatedly (there are also alternatives to matrix inversion that we will not discuss here). Your assignment is to write a pair of functions that cache the inverse of a matrix.

Write the following functions:

1. makeCacheMatrix: This function creates a special "matrix" object that can cache its inverse.
2. cacheSolve: This function computes the inverse of the special "matrix" returned by makeCacheMatrix above. If the inverse has already been calculated (and the matrix has not changed), then the cachesolve should retrieve the inverse from the cache.

Computing the inverse of a square matrix can be done with the solve function in R. For example, if X is a square invertible matrix, then solve(X) returns its inverse.

For this assignment, assume that the matrix supplied is always invertible.

In order to complete this assignment, you must do the following:

1. Fork the GitHub repository containing the stub R files at https://github.com/rdpeng/ProgrammingAssignment2 to create a copy under your own account.
2. Clone your forked GitHub repository to your computer so that you can edit the files locally on your own machine.
3. Edit the R file contained in the git repository and place your solution in that file (please do not rename the file).
4. Commit your completed R file into YOUR git repository and push your git branch to the GitHub repository under your account.
5. Submit to Coursera the URL to your GitHub repository that contains the completed R code for the assignment.

Grading:
This assignment will be graded via peer assessment. During the evaluation phase, you must evaluate and grade the submissions of at least 4 of your classmates. If you do not complete at least 4 evaluations, your own assignment grade will be reduced by 20%.
