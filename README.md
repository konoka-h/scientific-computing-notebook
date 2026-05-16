# AMATH 481 Computational Notebook  
## Scientific Computing for Quantitative Finance and Applied Mathematics

This repository contains my AMATH 481 computational notebook, created as a scientific computing archive and portfolio project.

The notebook focuses on numerical methods for solving problems from physics, including quantum mechanics, fluid dynamics, and reaction-diffusion systems. It also connects these computational techniques to applications in quantitative finance, computational finance, ESG finance, spillover effects, and time-series econometrics.

## Contents

The notebook includes three main computational projects:

### 1. Quantum Harmonic Oscillator

This section solves the time-independent Schrödinger equation as a boundary value problem and eigenvalue problem.

Implemented methods include:

- Shooting method
- Direct matrix method using finite differences
- Nonlinear extension using a double-loop shooting method

The section also connects eigenvalue problems and spectral decomposition to finance applications such as PCA, yield curve modeling, and financial network analysis.

### 2. Vorticity-Streamfunction Equations

This section simulates the 2D incompressible Navier-Stokes equations using the vorticity-streamfunction formulation.

Implemented methods include:

- Finite difference discretization
- Sparse matrix construction
- Direct solver
- LU decomposition
- BiCGSTAB
- GMRES
- FFT-based spectral solver

The section compares solver performance and includes vortex simulations and visualizations.

### 3. Reaction-Diffusion Systems

This section simulates a lambda-omega reaction-diffusion system that produces spiral wave patterns.

Implemented methods include:

- FFT method with periodic boundary conditions
- Chebyshev spectral method with Dirichlet boundary conditions
- 2D and 3D visualizations
- Spiral wave animation

The section connects reaction-diffusion systems to financial contagion, systemic risk, ESG sentiment diffusion, and market shock propagation.

## Numerical Methods Used

This notebook demonstrates several scientific computing techniques, including:

- Initial value problem solvers
- Boundary value problem methods
- Finite difference methods
- Sparse matrix methods
- Eigenvalue problems
- FFT and spectral methods
- Chebyshev differentiation
- Time-stepping methods
- Stability and diffusion-based modeling
- Scientific visualization and animation

## Tools and Libraries

The notebook is written in Python and designed to run in Google Colab.

Main libraries used:

- NumPy
- SciPy
- Matplotlib

## Purpose

I created this notebook as both a course archive for AMATH 481 and a personal reference for future research in Computational Finance & Risk Management.

Although the core examples come from physics, the underlying mathematical structures—eigenvalue problems, partial differential equations, diffusion equations, nonlinear dynamics, and spectral methods—are also important in quantitative finance, risk modeling, and applied mathematics more broadly.

## View the Notebook

You can view the exported HTML notebook here:

https://konoka-h.github.io/scientific-computing-notebook/notebook.html

## Author

Konoka Hamada  
University of Washington  
Computational Finance & Risk Management
