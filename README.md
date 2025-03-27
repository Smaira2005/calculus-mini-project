Numerical Integration Using the Midpoint Rule
Objective
This project aims to approximate the definite integral of the function 
𝑓
(
𝑥
)
=
𝑥
2
f(x)=x 
2
  over the interval [200, 300] using the Midpoint Rule. The Midpoint Rule is a numerical integration method that provides an approximation of the area under a curve by dividing the given interval into smaller subintervals and evaluating the function at the midpoint of each subinterval. The Python implementation in this project demonstrates how this method can be used to estimate definite integrals efficiently.

Implementation
The project employs a Python-based approach to calculate the integral approximation. The steps followed in the implementation include:

Defining the Function:

The function 
𝑓
(
𝑥
)
=
𝑥
2
f(x)=x 
2
  is defined in Python to be used in calculations.

Midpoint Rule Calculation:

The given interval [200, 300] is divided into a specified number of subintervals (n = 100 in this case).

The width of each subinterval is calculated as:

ℎ
=
𝑏
−
𝑎
𝑛
h= 
n
b−a
​
 
The function is then evaluated at the midpoint of each subinterval, and the sum of these evaluations is used to approximate the integral:

∫
𝑎
𝑏
𝑓
(
𝑥
)
𝑑
𝑥
≈
ℎ
∑
𝑓
(
midpoint
)
∫ 
a
b
​
 f(x)dx≈h∑f(midpoint)
The computed integral value is printed to the console.

Result:

The final approximation of the integral using the Midpoint Rule is 6,333,325.0.

Conclusion
The Midpoint Rule is a simple yet effective numerical method for approximating definite integrals, particularly useful when an analytical solution is difficult to obtain. The Python implementation provides a practical and efficient way to compute integral values, demonstrating the importance of numerical methods in calculus and applied mathematics.

This project highlights the use of computational tools to solve mathematical problems, reinforcing the concept of numerical integration and its applications in real-world scenarios.


