# Molecular Dynamics Simulations of “ion confinement and transport in hydrogel electrolytes”

This repository contains the LAMMPS input and data files used for molecular dynamics simulations of Zn2+ confinement and transport in **PAM** and **PAMPS** hydrogel electrolytes.

## Repository Structure

The repository contains two main folders:

* `PAM/`
* `PAMPS/`

Each folder contains five subfolders corresponding to different Zn2+ concentrations:

0.1M/
0.25M/
0.5M/
1M/
2M/

Each concentration folder contains the corresponding LAMMPS:

* `.in` file for simulation settings and procedures
* `.data` file containing the initial molecular configuration

## Electric Field Simulations

Both the `PAM` and `PAMPS` folders contain an additional `Efield/` folder.

The `.in` and `.data` files in these folders are used for nonequilibrium molecular dynamics simulations under externally applied electric fields to investigate the directional migration of Zn2+ ions.

## File Types

* `.in`: LAMMPS input files containing simulation settings and commands
* `.data`: LAMMPS data files containing molecular structures, topology, and initial configurations
