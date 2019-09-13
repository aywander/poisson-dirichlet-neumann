# poisson-dirichlet-neumann

A minimal working example in python of solving the Poisson equation with Dirichlet boundary conditions (BC) or Neumann boudnary conditions with discrete sine transforms (DST) or discrete cosine transforms (DCT), respectively, according to Numerical Recipes 3rd Edition, Chapter 20 Section 4.

This uses the methods of adding BC terms arising in the discretiziation to the RHS as source terms.

The problem solved is the potential source-term pair from Leveque's "Finite Difference Methods
for Ordinary and Partial Differential Equations" Section 4.6.1. (the section on Multigrid methods) Eqs 4.82 and 4.83.

Authors: A. Y. Wagner and Yuji Wama (Center for Computational Sciences, University of Tsukuba)
