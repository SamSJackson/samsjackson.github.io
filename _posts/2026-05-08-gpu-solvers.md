---
layout: post
title: Optimising Iterative Solvers for GPUs
date: 2026-04-08 00:09:00
description: We explore how one can optimise iterative solvers for solving on GPU systems
tags: [solvers, linear-algebra, gpu]
categories: sample-posts
---

## Basics of Linear Solvers
Linear systems arise frequently in the form of optimisation problems, particularly amidst the solving of PDEs. Through methods like the Finite Element Method (FEM) and the Finite Volume Method (FVM), systems of the form $\mathbf{A}x = b$, where $\mathbf{A}$ is a matrix and $x, b$ are vectors, must be solved.

Efficient solvers of these systems are a desirable commodity. The most recognisable techniques are likely Gaussian and LU decompositon, effective *direct* solvers. Whilst direct solvers are simple and provide analytical solutions, they have higher memory requirements, due to the fill-in factor. Meanwhile, iterative solvers aim to approximate the solution to the linear system by reducing the residual $r = b - \mathbf{A}x$. 

## Iterative Solvers



## Iterative Solvers on GPUs
