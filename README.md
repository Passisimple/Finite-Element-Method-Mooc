Assignment solutions for the Finite Element Method for Problems in Physics Mooc.
The mooc is taught by Prof. Dr. Krishna Garikipati from University of Michigan and consists of 4 assignments.
In assignments Deal.ii finite element library is utilized, the version of the deal.ii in the original course is 8.2.1.
Coding of the assignments is performed in a linux-ubuntu based OS, by using C++ language. 

Every assignment focuses on fundamental problems regarding to Finite Element Method. In each assignment a number of coding tasks are completed. 

Assignment 1:
  Focuses on Linear Elliptic PDE in One Dimension.
  - Basis Functions & Basis Function Gradients are defined.
  - Quadratule Rule is defined manually.
  - Local Force Vector & Stiffness Matrix are coded.
  - Dirichlett & Neumann Conditions are applied.
  - Force Vector & Stiffness Matrix are assembled.
  - L2 norm is calculated with the quadratulre rule.

Assignment 2:
  Focuses on Linear Elliptic PDEs in 2&3 Dimensions for scalar variable.
  - Basis Functions & Basis Function Gradients are defined.
  - Dirichlett & Neumann Conditions are applied.
  - Quadratule Rule is defined manually.
  - Local conductivity matrices are generated & assembled.

Assignment 3:
  Focuses on Linear Elliptic PDEs in 3 Dimensions for vector unknowns.
  - Dirichlett & Neumann Conditions are applied.
  - Local Force Vectors & Stiffness Matrices are generated.
  - Force Vector & Stiffness Matrix are assembled.

Assignment 4:
  Focuses on Linear Parabolic PDE for a scalar unknown in 3D
  - Dirichlett Boundary Conditions are applied to primary field & and its time derivative.
  - Local Mass & Conductivity Matrices are generated & assembled.
  - Initial conditions applied throught the domain.
  - Using a semi discrete solution procedure for time; Euler Family Methods are utilized. Namely Crank-Nicholson (alpha = 0.5), Forward Euler (alpha = 0) & Backward Euler (alpha = 1)
  (Solution did not obtained iteratively, so large matrix inversion processes are present.)
  - An L2norm is calculated to measure the difference between steady state solution & transient solution.
