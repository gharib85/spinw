---
title: sw_cartesian( )
keywords: sample
summary: "creates a right handed Cartesian coordinate system"
sidebar: product1_sidebar
permalink: sw_cartesian.html
folder: swfiles
mathjax: true
---
  creates a right handed Cartesian coordinate system
 
  [vy, vz, vx] = SW_CARTESIAN(n)
 
  V = SW_CARTESIAN(n)
 
  It creates an (x,y,z) right handed Cartesian coordinate system with vx,
  vy and vz defines the basis vectors. If only a single output is required,
  V will contain the basis vectors in a matrix: V = [vx vy vz].
 
  Input:
 
  n         Either a 3 element row/column vector or a 3x3 matrix with
            columns defining 3 vectors.
  Output:
 
  vy,vz,vx  Vectors defining the right handed coordinate system. They are
            either column of row vectors depending on the shape of the
            input n.
 