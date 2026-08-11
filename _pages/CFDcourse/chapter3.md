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
