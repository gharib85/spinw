---
title: sw_converter( )
keywords: sample
summary: "converts energy and momentum units for a given particle"
sidebar: product1_sidebar
permalink: sw_converter.html
folder: swfiles
mathjax: true
---
  converts energy and momentum units for a given particle
 
  out = SW_CONVERTER(value, unitIn, unitOut, {particleName}) 
 
  Input:
 
  particleName      Name of the particle:
                        'neutron'   default
                        'proton'
                        'electron'
                        'photon'
  value             Numerical input value, can be arbitrary matrix.
  unitIn            Units of the input value:
                        'A-1'       momentum in Angstrom^-1.
                        'k'         -||-
                        'Angstrom'  wavelength in Angstrom.
                        'lambda'    -||-
                        'A'         -||-
                        'Kelvin'    temperature in Kelvin.
                        'K'         -||-
                        'mps'       speed in m/s.
                        'J'         energy in Joule.
                        'meV'       energy in meV.
                        'THz'       frequency in Thz.
                        'cm-1'      2*pi/lambda in cm^-1.
                        'eV'        energy in eV.
                        'fs'        wave period time in fs.
                        'ps'        wave period time in ps.
                        'nm'        wavelength in nm.
                        'um'        wavelength in um.
  unitOut           Units of the output value, same options as for unitIn.
 