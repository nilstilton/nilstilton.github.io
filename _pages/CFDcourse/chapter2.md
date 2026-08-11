---
title: "Chapter 2: Finite Difference Methods"
layout: single
permalink: /CFDcourse/chapter2/
header:
  image: /assets/images/cfd-ch2-banner.jpg
  image_description: "Contents of textbook chapter 2"
classes: wide
---

## Overview

This chapter reviews finite-difference approximations for derivatives —
forward, backward, and centered differences — along with the concepts of
truncation error and order-of-accuracy. These tools are used extensively
in finite-volume methods and throughout the rest of the course. The
companion programming chapter applies these formulas in C++ to compute
the vorticity field within a laminar boundary layer.

## Theory

**Chapter 2 — Finite Difference Methods**

[Download the theory chapter (PDF)](/assets/CFDcourse/pdfs/textbook-ch2.pdf){: .btn .btn--primary}

Topics covered: forward, backward, and centered difference formulas;
stencils; truncation error and order-of-accuracy; measuring local and
global error; estimating observed order-of-accuracy from log-log error
plots; and (optional reading) additional finite-difference formulas for
second-order accurate first derivatives on non-uniform grids, one-sided
differences, and second derivatives.

## Homework

**Chapter 2 — Using C++ Arrays, Loops, and Math Functions**

[Download the homework chapter (PDF)](/assets/CFDcourse/pdfs/homework-ch2.pdf){: .btn .btn--primary}

Topics covered: declaring constants with `const`, for-loops and variable
scope, C-style arrays, and the `cmath` header. The end-of-chapter
assignment uses centered and one-sided finite differences (Chapter 2
theory) to compute the vorticity profile in a laminar boundary layer,
verify the observed order-of-accuracy against the expected rate, and
interpret the resulting vorticity profile physically.

**Lecture 3: Finite Differences and Order-of-Accuracy**

<iframe width="560" height="315" src="https://www.youtube.com/embed/msa0l5ZSPzI"
title="Lecture 3: Finite Differences and Order-of-Accuracy"
frameborder="0" allowfullscreen></iframe>
