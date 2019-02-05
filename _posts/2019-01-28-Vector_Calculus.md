---
layout:     post
title:      Tensor essence
subtitle:    "\"Vector calculus\""
date:       2019-02-04
author:     BY
header-img: img/post-bg-2015.jpg
catalog: true
tags:
    - Math
    - Tensor
    - Vector
---
# Lecture 3

1. Vector calculus

   + a scalars;
   + b vector;
   + c tensor;

2. Index notation
3. Examples - applictoins - identities
4. Intorduction to fluid mechanics
5. Clarification on HWK1

## Tensor

$n^{th}$ order tensor.
Scalar is the $0^{th}$ order tensor
Vector is the $1^{th}$ order tensor

Tensors
$n^{th}$

$\vec{u}=u_i\cdot\hat{e}_i$

$\delta_{ij}\cdot u_j=\delta_{i1}\cdot u_1 + \delta_{i2}\cdot u_2 + \delta_{i3}\cdot u_3 = u_i=(u_1, u_2, u_3)$

$\hat{e}_i \cdot \hat{e}_j = \delta_{ij}$
Scalar product of two vectors
$\vec u, \vec v$ are the vectors.

$\epsilon_{ijk}=\epsilon_{jki}=\epsilon_{kij}$

$\vec{u}\times \vec{v} = \epsilon_{ijk} \cdot \hat{e}_i u_j v_k$

$\frac{\partial\phi}{\partial n}=\nabla\phi\cdot\hat n$

$\nabla\cdot\vec u = \frac{\partial u}{\partial x} + \frac{\partial u}{\partial y} + \frac{\partial w}{\partial y}=\frac{\partial u_j}{\partial x_j}$

$B_{ij}=B_{ji}$ symmetrie
$B_{ij}=-B_{ji}$ anti-symmetrie
$B_{ii}=-B-{ii} => B_{ii} = 0$ AsM: Zero Diorgonal

$A_{ij} = \frac{1}{2}A_{ij} + \frac{1}{2}A_{ij}=\frac{1}{2}A_{ij} + \frac{1}{2}A_{ji} + \frac{1}{2}A_{ij} - \frac{1}{2}A_{ji}=\frac{1}{2}(A_{ij} + A_{ji}) + \frac{1}{2}(A_{ij} - A_{ji})=symmetric + {anti-symmetric}$