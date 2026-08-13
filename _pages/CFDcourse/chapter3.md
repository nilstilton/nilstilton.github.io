---
title: "Chapter 3: Introduction to Finite Volume Methods (Steady Heat Conduction)"
layout: single
permalink: /CFDcourse/chapter3/
header:
  image: /assets/images/cfd-ch3-banner.jpg
  image_description: "Contents of textbook chapter 3"
classes: wide
---

## Overview

This chapter introduces the finite-volume method 
using the steady heat conduction equation as a 
simple, non-advective starting point. It covers 
the two core steps of finite-volume discretization  
(approximating integrals and approximating face values) 
along with boundary conditions via ghost nodes, 
assembly of the global sparse matrix, and a 
complete worked example verified using the 
method of manufactured solutions.

## Theory

**Chapter 3 — Introduction to Finite Volume Methods: Steady Heat Conduction**

[Download the theory chapter (PDF)](/assets/CFDcourse/pdfs/textbook-ch3.pdf){: .btn .btn--primary}

Topics covered: Cartesian finite-volume grids; spatial discretization
(approximating integrals and face values); linear and harmonic-mean
interpolation of face conductivities; the 5-point stencil; boundary
conditions via boundary nodes, ghost nodes, and reduced stencils;
assembling the global sparse matrix; coding and verifying a 2D steady
heat conduction solver in MATLAB using the method of manufactured
solutions; and guidelines for physically reliable finite-volume
discretizations (consistent fluxes, positive coefficients, the
sum-of-neighbors rule, and boundedness).

## Homework

**Chapter 3 — C++ Vectors and Writing Output to File**

[Download the homework chapter (PDF)](/assets/CFDcourse/pdfs/homework-ch3.pdf){: .btn .btn--primary}

Topics covered: C++ vectors (dynamic arrays whose size is set at run
time), vector member functions, and writing data to file using
`ofstream`. The end-of-chapter assignment guides you through building a
complete finite-volume solver for the 2D steady heat conduction equation
with constant conductivity: assembling the sparse coefficient matrix,
building the right-hand-side vector, solving the linear system with
Eigen, and verifying the solver using the method of manufactured
solutions. The verified solver is then applied to simulate a heat fin
with inconsistent corner boundary conditions, including a grid
sensitivity study that reveals a hidden singularity in the solution.

## Lectures

**Lecture 4: Finite-Volume Discretization of Steady Heat Conduction**

<iframe width="560" height="315" src="https://www.youtube.com/embed/taGh7idWYVA"
title="Lecture 4: Finite-Volume Discretization of Steady Heat Conduction"
frameborder="0" allowfullscreen></iframe>

**Lecture 5: Applying Boundary Conditions in Finite-Volume Methods**

<iframe width="560" height="315" src="https://www.youtube.com/embed/i5hcexNPQI8"
title="Lecture 5: Applying Boundary Conditions in Finite-Volume Methods"
frameborder="0" allowfullscreen></iframe>

**Lecture 6: Assembling the Global Matrix System** 

<iframe width="560" height="315" src="https://www.youtube.com/embed/Qpllq7_GHf0"
title="Lecture 6: Assembling the Global Matrix System"
frameborder="0" allowfullscreen></iframe>

**Lecture 7: Memory, Sparsity, and Linear Solvers in Finite-Volume Methods**

<iframe width="560" height="315" src="https://www.youtube.com/embed/JXjqs3NIe1Q"
title="Lecture 7: Memory, Sparsity, and Linear Solvers in Finite-Volume Methods"
frameborder="0" allowfullscreen></iframe>

