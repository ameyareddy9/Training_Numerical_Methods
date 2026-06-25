# Finite Difference Simulation of Diffusion and Elasticity Problems

## Overview

This project implements **Finite Difference Method (FDM)** based numerical solvers for ordinary differential equations (ODEs) and partial differential equations (PDEs) arising in heat transfer and solid mechanics.

The work includes diffusion problems, axisymmetric elasticity of hollow and solid cylinders, sparse matrix formulations, and validation against analytical solutions.

The objective is to study how engineering boundary value problems can be transformed into algebraic systems and solved computationally.

---

## Topics Covered

### 1. Boundary Value ODE

Numerical solution of a second-order ordinary differential equation using central finite differences.

**Highlights**
- Finite difference discretization
- Matrix formulation
- Comparison with analytical solution
- Error visualization

---

### 2. One-Dimensional Diffusion Equation

Numerical simulation of transient diffusion in a one-dimensional domain.

**Highlights**
- Time-dependent PDE
- Explicit finite difference scheme
- Evolution of concentration profile
- Stability considerations

---

### 3. Hollow Cylinder Elasticity

Axisymmetric stress-displacement analysis of a thick-walled cylinder subjected to pressure loading.

**Highlights**
- Cylindrical coordinate formulation
- Non-dimensionalization
- Sparse matrix assembly using SciPy
- Validation against analytical elasticity solution

**Governing Equation**

```text
d²u/dr² + (1/r)(du/dr) - u/r² = 0
```

---

### 4. Cylindrical Diffusion Equation

Transient diffusion in an axisymmetric cylindrical domain.

**Highlights**
- Radial diffusion equation
- Treatment of singularity at r = 0
- L'Hospital-based discretization
- Time evolution of concentration field

---

### 5. Solid Cylinder Elasticity

Radial displacement analysis of a solid cylinder.

**Highlights**
- Axisymmetric elasticity
- Symmetry boundary condition at center
- Numerical vs analytical comparison
- Stress and displacement visualization

---

## Numerical Methods Used

- Finite Difference Method (FDM)
- Central Difference Approximation
- Sparse Matrix Formulation
- Linear System Solution using SciPy Sparse Solvers
- Analytical Validation

---

## Tools and Libraries

- Python
- NumPy
- SciPy
- Matplotlib
- Google Colab

---

## Key Learning Outcomes

- Discretization of differential equations
- Numerical treatment of boundary conditions
- Sparse linear algebra for engineering systems
- Axisymmetric elasticity modeling
- Diffusion and transport phenomena simulation
- Validation of numerical methods against exact solutions

---
