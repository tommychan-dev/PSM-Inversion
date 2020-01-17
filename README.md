# PSM-Inversion
PSM Matlab inversion code (DOI: https://zenodo.org/badge/latestdoi/223453115)

PSM Inversion script v1.0 (3 Dec 2019)
Author: Tommy Chan (tommy.chan@helsinki.fi)
Last updated: 3 Dec 2019
Coded with MATLAB R2019a.

 == START SCRIPT with Inversion_Comp_Run.m ==
 
 ** Note: If using loss correction, i.e., line 56 is 1 or 2, change parameters in Loss_Correction.m file
 e.g. Length of tubes, flows

Bugs:
-Selecting particular size diameters may result in code error. Adjust upper and lower size bin.

Future updates may include:
-background measurements
-inversion of step mode measurements
-inversion using pre-exisiting kernel functions
