---
title: translate( )
keywords: sample
summary: "translate objects on swplot figure"
sidebar: product1_sidebar
permalink: translate.html
folder: +swplot
mathjax: true
---
  translate objects on swplot figure
 
  SWPLOT.TRANSLATE(mode, {hFigure})
 
  The function translates the objects of an swplot, where the coordinate
  system is defined by the plane of the figure with horizontal x-axis,
  vertical y-axis and out-of-plane z-axis.
 
  Input:
 
  mode      Either a vector with three elements determining the translation 
            value in the figure plane coordinate system, or 'auto' that
            centers the object on the figure. Default is 'auto'.
  hFigure   Handle of the swplot figure window, optional.
 
  See also SWPLOT.ZOOM.
 