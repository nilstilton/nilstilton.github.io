---
title: "Chapter 4: Grid Convergence Studies"
layout: single
permalink: /CFDcourse/chapter4/
header:
  image: /assets/images/cfd-ch4-banner.jpg
  image_description: "Contents of textbook chapter 4"
classes: wide
---

## Overview

Grid convergence studies are a set of best practices for checking
whether a simulated quantity has become independent of grid
resolution — and for catching cases where a simulation looks fine
but isn't. This chapter works through the theory and a complete
worked example using heat transfer through an aluminum fin.

## Theory

**Chapter 4 — Grid Convergence**

[Download the theory chapter (PDF)](/assets/CFDcourse/pdfs/textbook-ch4.pdf){: .btn .btn--primary}

Topics covered: assumptions underlying grid convergence studies;
choosing a characteristic cell size $h$ for uniform, non-uniform,
and unstructured grids; the asymptotic and pre-asymptotic regimes;
estimating the observed order-of-accuracy $p$ from three
progressively refined grids; classifying convergence behavior
(monotonic and oscillatory convergence and divergence); checking
consistency between observed and expected order-of-accuracy;
estimating discretization error via the approximate and
extrapolated relative errors; the Grid Convergence Index (GCI);
and a case study on heat transfer through an aluminum fin showing
how inconsistent boundary conditions can degrade accuracy without
any visible sign in the simulated temperature field.

## Homework