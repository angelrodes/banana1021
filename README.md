# Banana calculator for Be-10 and Ne-21 data

A script that works in Matlab or Octave and solves burial ages iteratively.

This script for Matlab and Octave calculates iteratively erosion rates and burial times from cosmogenic 10Be and 21Ne concentrations scaled to their catchment average production rates. Concentration data is defined in the file ```samples.csv```.

The distribution of spallation and muon relative production rates are defined in the file ```procuctions.csv```. They can be calculated using [this approach](https://angelrodes.wordpress.com/2021/12/15/average-cosmogenic-production-rate-calculator/), or just with the latitude-elevation approximations defined in [Rodés (2021)](https://doi.org/10.3390/geosciences11090362).

Concentrations in ```samples.csv``` are usually scaled to surface prodution rates. If so, protuction rates in ```productions.csv``` should also be scaled to surface prodution rates.

The graphical outputs are a banana plot, and the results in the time-erosion rate space.

In the command window, results are shown as ranges derived from the concentration uncertainties.
