---
layout: default
title: Home
---

<nav class="page-toc" aria-label="On this page">
<a href="#selected-skills">Skills</a>
<a href="#resume">Resume</a>
<a href="#education">Education</a>
<a href="#professional-experience">Experience</a>
<a href="#technical-skills">Technical Skills</a>
<a href="#publications">Publications</a>
<a href="#contact">Contact</a>
</nav>

# About Me

I am a computational physicist (Ph.D.) with 10+ years writing scientific code, running computational experiments, and validating models against data. I currently evaluate frontier language models on expert-level physics reasoning and build neural-network surrogates of expensive simulations. I am the author of open-source scientific libraries ([Paramo](/projects/#paramo), [Tleco](/projects/#tleco); *ApJ* 2024) with code review and unit testing, and a mentor of graduate students. Growing up in the highlands of central Mexico, I developed a deep appreciation for natural landscapes, which continues to fuel my applied research in environmental and physical systems.

## Selected Skills

- Scientific machine learning & surrogate modeling
- Computational modeling, simulation & HPC
- Language-model evaluation (scientific reasoning)
- Geospatial analysis & terrain modeling
- Data analysis & visualization
- Scientific communication

## Resume

- [Resume (PDF)](https://github.com/altjerue/jmrb_cv/blob/master/resume-RuedaBecerrilJM.pdf?raw=true)
- [Full CV (PDF)](https://github.com/altjerue/jmrb_cv/blob/master/cv-RuedaBecerrilJM.pdf?raw=true)

## Education

- **Ph.D. in Physics** — Universitat de València, Spain (Jul 2017, *Excellent Cum Laude*). Advisors: Prof. Miguel A. Aloy & Dr. Petar Mimica. [Thesis](http://roderic.uv.es/handle/10550/60003)
- **M.Sc. in Physics** — Universidad Michoacana de San Nicolás de Hidalgo, Mexico (Sep 2011). Advisor: Prof. José A. Cervera
- **B.Sc. in Physics** — Universidad Autónoma del Estado de México, Mexico (Dec 2008). Advisor: Prof. Francisco S. Guzmán

## Professional Experience

**Independent Contractor** — Mercor (Jan 2026 – Present)
- Physics subject-matter expert evaluating frontier language models for multiple leading AI labs.
- Review 50+ expert-level physics, hydrodynamics, astrophysics, and cosmology problems; write original prompts that stump frontier models and diagnose failure modes in their reasoning.

**Spatial Data Scientist** — TealWaters (May 2025 – Jan 2026)
- Built geospatial ML pipelines and optimized terrain-analysis code for wetland mapping.
- Optimized the terrain-modeling code that computes elevation derivatives from 1 m, 3 m, and 10 m DEMs over 20 tiles, improving its computational performance.
- Mapped wetland probability across the 2,160 km² Skykomish watershed with the Wetland Intrinsic Potential (WIP) random-forest model, reaching >75% accuracy.

**Independent Researcher & Open-Source Developer** — Self-directed (Jan 2024 – May 2025)
- Co-developed [`Tleco`](/projects/#tleco), a Rust/Python toolkit that solves the Fokker–Planck equation coupled to radiative transfer to model radiation from relativistic outflows (*ApJ* 2024).
- Developing [`WindsOfChange`](/projects/#windsofchange) with the UW Forest Mycobiome Lab: a C++/R library that simulates wind-driven spore dispersal over forested, hilly terrain, parallelized with RcppParallel and OpenMP.

**Software Engineer** — Paychex (Apr 2022 – Jan 2024)
- Built and tested data-integration services between enterprise systems and Oracle E-Business Suite.
- Developed and tested production data-pipeline software (Java, Python, SQL) with CI/CD.

**Postdoctoral Research Associate** — Rochester Institute of Technology (Feb 2021 – Apr 2022)
- HPC simulations of supermassive black hole binaries in an NSF-funded project.
- Led a 7-person team upgrading `PatchworkMHD`, a C code for MHD simulations of supermassive black hole binaries; added black hole spin with under 5% runtime overhead.
- Ran and benchmarked large production simulations on Frontera (TACC), about 10,000 node-hours, and identified performance bottlenecks in the parallel code.
- Calibrated `Paramo` against Fermi-LAT gamma-ray spectra with gradient-based optimization that updates the model automatically; supervised a graduate student on the same problem.
- Co-authored 2 papers from a multi-institution study of binary neutron star mergers.

**Postdoctoral Research Fellow** — Purdue University (Oct 2018 – Nov 2020)
- Radiative-transfer modeling of relativistic jets (blazars and gamma-ray burst afterglows).
- Designed and wrote [`Paramo`](/projects/#paramo), an open-source Fortran 95 library that solves the Fokker–Planck equation for relativistic particle distributions coupled to radiative transfer; optimized it with OpenMP and tested GPU offload with OpenACC.
- Implemented implicit PDE solvers, numerical integration, and arbitrary-shape particle distributions without slowing the simulation.
- Wrote Python tools to analyze `Paramo` output and run parameter optimization; other groups have adopted `Paramo`, including Combi & Siegel (2023).
- Served as Co-I on two NASA Fermi Guest Investigator grant proposals, one funded ($68K) to model blazar radiation; mentored 3 graduate students and published 2 peer-reviewed papers.

**Postdoctoral Research Fellow** — Universidad Michoacana de San Nicolás de Hidalgo (Jan – Sep 2018)
- Developed a Python pipeline to process black hole simulation outputs from the `GRTrans` numerical code, generating SVM training data for radio image prediction.
- Built open-source data analysis and visualization tools in Python for radiative transfer phenomena in relativistic astrophysics scenarios.

**Graduate Research Assistant** — Universitat de València (Oct 2011 – Jul 2017)
- Studied how magnetization of shocked plasma shapes the radiation spectra of relativistic internal shocks, using the `C-SPEV` simulation code.

## Technical Skills

- **Languages:** Python, C/C++, R, Rust, SQL, Fortran 95, Java, Julia, Shell
- **ML & Data:** Scientific machine learning, language-model evaluation, surrogate modeling, Bayesian inference, Gaussian process regression, PyTorch, scikit-learn, TensorFlow, random forest, neural networks, SVM, gradient-based optimization, ML-assisted parameter estimation, NumPy, SciPy, Pandas, Astropy
- **Geospatial:** Sentinel-1/2 multispectral processing, DEM terrain analysis, raster/vector data pipelines, QGIS
- **HPC & Parallel:** OpenMP, OpenACC (GPU offloading), MPI, SLURM, PBS, HDF5
- **Tools:** Git, Docker, Azure, Jenkins, OpenShift, Kafka, Splunk, Jira, ParaView, VisIt

## Publications

**Selected** (9 published articles, 3 first-author; 3 in preparation):

- Davis, Z., Rueda-Becerril, J.M., Giannios, D. (2024). "Tleco: A Toolkit for Modeling Radiative Signatures from Relativistic Outflows". *The Astrophysical Journal*, 976(2), 182. [DOI:10.3847/1538-4357/ad8bc2](https://doi.org/10.3847/1538-4357/ad8bc2)
- Davis, Z., Rueda-Becerril, J.M., Giannios, D. (2022). "Balancing turbulent heating with radiative cooling in blazars". *Monthly Notices of the Royal Astronomical Society*, 513(4), 5766-5779. [DOI:10.1093/mnras/stac1282](https://doi.org/10.1093/mnras/stac1282)
- Rueda-Becerril, J.M., Harrison, A.O., Giannios, D. (2021). "Blazar jets launched with similar energy per baryon, independently of their power". *Monthly Notices of the Royal Astronomical Society*, 501(3), 4092-4102. [DOI:10.1093/mnras/staa3925](https://doi.org/10.1093/mnras/staa3925)
- Rueda-Becerril, J.M., Mimica, P., Aloy, M.A. (2017). "On the influence of a hybrid thermal-non-thermal distribution in the internal shocks model for blazars". *Monthly Notices of the Royal Astronomical Society*, 468(2), 1169-1182. [DOI:10.1093/mnras/stx476](https://doi.org/10.1093/mnras/stx476)
- Guzmán, F.S., Rueda-Becerril, J.M. (2009). "Spherical boson stars as black hole mimickers". *Physical Review D*, 80, 084023. [DOI:10.1103/PhysRevD.80.084023](https://doi.org/10.1103/PhysRevD.80.084023)

Full list: [ADS](https://ui.adsabs.harvard.edu/#search/q=author%3A%22Rueda-Becerril%2C%20J.%20M.%22&sort=date%20desc%2C%20bibcode%20desc&p_=0) · [arXiv](https://arxiv.org/search/astro-ph?searchtype=author&query=Rueda-Becerril%2C+J+M) · [Google Scholar](https://scholar.google.com/citations?user=hrld5zgAAAAJ)

## Personal Interests

Beyond astrophysics, science, the environment, and computers, I love hiking and climbing mountains.

## Languages

- Spanish: native proficiency (talks and teaching in Spanish)
- English: full professional proficiency
- Catalan: basic knowledge
- Nahuatl: basic knowledge

## Contact

- [Email](mailto:jm.ruebe@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/jeruebe)
- [ResearchGate](https://www.researchgate.net/profile/Jesus_Rueda-Becerril)
- [GitHub](https://www.github.com/altjerue)
- [ORCID](https://orcid.org/0000-0003-1988-1912)

<p class="back-to-top"><a href="#">↑ Back to top</a></p>
