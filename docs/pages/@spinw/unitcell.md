---
title: unitcell( )
keywords: sample
summary: "returns information on atoms in the crystallographic unit cell"
sidebar: product1_sidebar
permalink: unitcell.html
folder: @spinw
mathjax: true
---
  returns information on atoms in the crystallographic unit cell
 
  unit_cell_info = UNITCELL(obj, idx)
 
  The function returns information on symmetry inequivalent atoms. 
 
  Input:
 
  obj       spinw class object.
  idx       Selects certain atoms. If undefined UNIT_CELL(obj) or
            obj.UNIT_CELL returns information on all atoms. The selection
            can be also done according to the atom labels, in this case
            either a string of the label or cell of strings for several
            labels can be given.
 
  Output:
 
  'unit_cell_info' is a tructure with that contains all the fields of
  unit_cell.
 
  Example:
 
  ...
  cryst.unit_cell = unitcell(cryst,[1 3]);
 
  The example keeps only the first and third symmetry inequivalent atoms in
  cryst object.
 
  ...
  cryst.unit_cell = unitcell(cryst,'O');
 
  The example keeps only the Oxygen atoms in cryst object.
 
  See also SPINW.ADDTWIN, SPINW.TWINQ, SPINW.UNIT_CELL.
 