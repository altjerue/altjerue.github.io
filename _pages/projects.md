---
permalink: /projects/
layout: default
title: Projects
---

# Projects

<!-- 
# TODO
- [ ] Add images to each project
- [ ] Add links to project pages or repositories
- [X] Add the technologies used in each project
- [ ] Add "Matlatsinko" project
-->

## [Wind and Spores](https://github.com/UW-ForestMycobiomeLab/WindSporesHills)  | Aug 2024 -- May 2025

- Open Source Code for Dispersion of Spores in Hilly Terrains.
- Simulate the dispersion of spores in hilly terrains in R and C++.

**Used:** C++, Git, R: RStudio, Rcpp, ggplot2, dplyr, tidyr

## [Tleco](https://github.com/zkdavis/Tleco)  | Jan 2024 -- Sep 2024

- `Tleco` stands for both *in the fire* and *rise* in the nahuatl language.
- Open Source Code for Simulation of Relativistic Particles Radiation
- Numerical code that simulates particles in relativistic plasma, and the rise of radiation from accelerating particles.
- Consists of both Rust functions and Python functions previously built in the Fortran code `Paramo`.

**Used:** Rust, HDF5, Git, Python: Numpy, Matplotlib, Scipy

#### Publications using `Tleco`

- Davis, Z., Rueda-Becerril, J.M., Giannios, D. (2024). "Tleco: A Toolkit for Modeling Radiative Signatures from Relativistic Outflows". *The Astrophysical Journal*, 976(2), 182, 12. [DOI:10.3847/1538-4357/ad8bc2](https://doi.org/10.3847/1538-4357/ad8bc2) 

## [Paramo](https://github.com/altjerue/paramo)  | Oct 2018 -- Apr 2022

- Open Source Code for Radiative Transfer Simulations in Relativistic Astrophysics
- Independently developed this code for distributed settings to perform HPC simulations of radiative transfer in relativistic astrophysics.
- Optimized the code with OpenMP to reduce simulation time from 2 minutes to 5 seconds.
- Researched and applied mathematical concepts of machine learning (gradient descent) to adjust the parameters of the code to classify observations from NASA telescopes.
- This code has been used for at least 5 scientific publications and also for graduate pedagogical purposes.
- Developed data analysis and data visualization tools in Python.

**Used:** Fortran, HDF5, OpenMP, Git, Python: Numpy, Pandas, Matplotlib, Scipy

#### Publications using `Paramo`

- Rueda-Becerril, J.M., Harrison, A.O., Giannios, D. (2021). "Blazar jets launched with similar energy per baryon, independently of their power". *Monthly Notices of the Royal Astronomical Society*, 501(3), 4092-4102. [DOI:10.1093/mnras/staa3925](https://doi.org/10.1093/mnras/staa3925)
- Rueda-Becerril, J.M., Harrison, A.O., Giannios, D. (2021). "The blazar sequence revised". Astronomische Nachrichten, Volume 342, Issue 1-2, pp. 147-152. [DOI:10.1002/asna.202113895](https://doi.org/10.1002/asna.202113895)
- Rueda-Becerril, J.M. (2021). "A numerical approach for radiative cooling in relativistic outflows". Astronomische Nachrichten, Volume 342, Issue 1-2, pp. 277-282. [DOI:10.1002/asna.202113919](https://doi.org/10.1002/asna.202113919)
- Davis, Z., Rueda-Becerril, J.M., Giannios, D. (2022). "Balancing turbulent heating with radiative cooling in blazars ". *Monthly Notices of the Royal Astronomical Society*, 513(4), 5766-5779. [DOI:10.1093/mnras/stac1282](https://doi.org/10.1093/mnras/stac1282)
- Combi, L., Siegel, D.M. (2023). "GRMHD Simulations of Mergers with Weak Interactions: r-process Nucleosynthesis and Electromagnetic Signatures of Dynamical Ejecta". *The Astrophysical Journal*, 944(1), 29. [DOI:10.3847/1538-4357/acac29](https://doi.org/10.3847/1538-4357/acac29)

<!-- 
# Code Development

+ [PypersPlots](https://altjerue.github.io/PypersPlots)
+ [emacs-init-file](https://altjerue.github.io/emacs-init-file)

 - Theory and observation of high energy radiation in different scenarios where black holes are involved
  - Radiation transport
  - Radiation source and source region
  - Particles acceleration processes
- Active galactic nuclei
  - Blazars
    - Acceleration processes in the emission region
    - Location of the emission region
    - The spectral effects due to different constituents of the material in the emission region
  - Radio galaxies
  - Quasars
  - Tidal disruption events
- Microquasars
- Gamma-ray bursts
- Pulsars
- X-ray binaries

- Numerical solutions to the radiation transport equation with astrophysical applications.
- Numerical treatment of the microphysics involved in the emission of high energy radiation.
- Numerical hydrodynamics and magnetohydrodynamics.
- Performance, stability, convergence and accuracy of numerical codes.

- Solutions to the Einstein equations

### Computer Sciences
- Decision-making optimization.
- Machine learning (supervised and unsupervised).
- Neuronal networks.
- Text mining.
- Network analysis. 
-->
