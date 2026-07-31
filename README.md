# Numerical Linear Algebra

Coursework projects from Numerical Linear Algebra (UPC, Mathematics degree), applying 
linear algebra methods — implemented from scratch — to physical and scientific problems.

## 01 — Orbit Determination of Asteroids
Determined an asteroid's orbit from optical observations using Laplace's method. 
Implemented QR decomposition from scratch to fit a second-order approximation of the 
asteroid's angular position, and vector norms (L1, Euclidean, infinity) to select the 
most physically consistent solution among the roots of Laplace's polynomial. Matched the 
resulting orbital elements against a database of 2,024 numbered asteroids, correctly 
identifying the object as asteroid **698 Ernestina**.

## 02 — Stationary Heat Equation
Solved the 1D and 2D stationary heat equation (Poisson's equation with Dirichlet boundary 
conditions) using the finite difference method, implementing an efficient, vectorized 
Jacobi iterative solver that avoids explicitly building the (sparse) system matrix.

## Tools
Python · NumPy · Pandas

## Notes
Core numerical routines (QR decomposition, Jacobi iteration) implemented manually as part 
of the coursework, without relying on built-in linear algebra solvers.
