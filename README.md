# Scientific Computing Software Collection (Fortran)

A curated catalog of scientific computing software written in Fortran (77 through modern Fortran 2018), organized by domain.

Archiving workflow and project trace to-dos: [ARCHIVE_TRACES_TODO.md](ARCHIVE_TRACES_TODO.md).

---

## Table of Contents

1. [Numerical Linear Algebra](#1-numerical-linear-algebra)
2. [Climate, Ocean & Weather Modeling](#2-climate-ocean--weather-modeling)
3. [Earth Science & Geophysics](#3-earth-science--geophysics)
4. [GFDL Ecosystem (NOAA)](#4-gfdl-ecosystem-noaa)
5. [Computational Fluid Dynamics](#5-computational-fluid-dynamics)
6. [Molecular Dynamics / Quantum Chemistry / Materials Science](#6-molecular-dynamics--quantum-chemistry--materials-science)
7. [Astrophysics / Space Science](#7-astrophysics--space-science)
8. [Finite Element / Structural Analysis](#8-finite-element--structural-analysis)
9. [Optimization & Mathematical Libraries](#9-optimization--mathematical-libraries)
10. [General Fortran Libraries & Frameworks](#10-general-fortran-libraries--frameworks)

---

## 1. Numerical Linear Algebra

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **BLAS** | Reference Basic Linear Algebra Subprograms for vector and matrix operations | https://www.netlib.org/blas/ | Open-source | Verified (unspecified) | Open-source verified |
| **LAPACK** | Linear Algebra PACKage — linear systems, eigenvalue problems, SVD (Fortran 90) | https://github.com/Reference-LAPACK/lapack | Open-source | modified BSD license | Open-source (modified BSD license) |
| **ScaLAPACK** | Scalable LAPACK for distributed-memory parallel computers via MPI | https://www.netlib.org/scalapack/ | Open-source | Verified (unspecified) | Open-source verified |
| **ARPACK-NG** | Large-scale sparse eigenvalue problems via implicitly restarted Arnoldi method | https://github.com/opencollab/arpack-ng | Open-source | BSD | Open-source (BSD) |
| **MUMPS** | MUltifrontal Massively Parallel Sparse direct solver (Fortran 95, MPI) | https://mumps-solver.org/ | Open-source | Verified (unspecified) | Open-source verified |
| **PARDISO** | Parallel direct sparse solver in Intel oneAPI MKL | https://www.intel.com/content/www/us/en/docs/onemkl/ | Restricted | N/A | Not open-source / restricted |
| **LINPACK** | Classic library for linear equations and least-squares (predecessor to LAPACK) | https://www.netlib.org/linpack/ | Open-source | Verified (unspecified) | Open-source verified |
| **EISPACK** | Eigenvalue/eigenvector computation (predecessor to LAPACK) | https://www.netlib.org/eispack/ | Open-source | Verified (unspecified) | Open-source verified |
| **FEAST** | Eigenvalue solver based on accelerated subspace iteration within intervals | https://feast.ecs.umass.edu/ | Open-source | [BSD-3-Clause](https://github.com/feast-dev/feast/blob/master/LICENSE) | Open-source ([BSD-3-Clause](https://github.com/feast-dev/feast/blob/master/LICENSE)) |
| **fortran-lapack** | Modern Fortran interface to LAPACK | https://github.com/perazz/fortran-lapack | Open-source | BSD-3-Clause license | Open-source (BSD-3-Clause license) |
| **SparseKit** | Tool-kit for sparse matrix computations (format conversion, I/O, sorting) | https://www-users.cse.umn.edu/~saad/software/SPARSKIT/ | Open-source | Verified (unspecified) | Open-source verified |
| **PSBLAS** | Parallel Sparse BLAS for distributed-memory sparse operations | https://github.com/sfilippone/psblas3 | Open-source | Verified (unspecified) | Open-source verified |
| **MLD2P4** | Multilevel Domain Decomposition Parallel Preconditioners (Fortran 2003) | https://github.com/sfilippone/mld2p4-2 | Open-source | Verified (unspecified) | Open-source verified |

---

## 2. Climate, Ocean & Weather Modeling

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **WRF** | Weather Research and Forecasting model — most widely used mesoscale NWP system | https://github.com/wrf-model/WRF | Open-source | Verified (unspecified) | Open-source verified |
| **MPAS** | Model for Prediction Across Scales — unstructured-mesh atmosphere/ocean/sea-ice | https://github.com/MPAS-Dev/MPAS-Model | Open-source | Verified (unspecified) | Open-source verified |
| **CESM** | Community Earth System Model — fully-coupled global climate model (CAM+CLM+POP+CICE) | https://github.com/ESCOMP/CESM | Open-source | Verified (unspecified) | Open-source verified |
| **ROMS** | Regional Ocean Modeling System — free-surface terrain-following ocean model | https://github.com/myroms | Open-source | MIT | Open-source (MIT) |
| **NEMO** | Nucleus for European Modelling of the Ocean (Fortran 2008) | https://forge.nemo-ocean.eu/nemo/nemo | Open-source | Verified (unspecified) | Open-source verified |
| **ICON** | ICOsahedral Non-hydrostatic model — unified weather/climate system (DWD + MPI-M) | https://code.mpimet.mpg.de/projects/iconpublic | Open-source | BSD-3-Clause | Open-source (BSD-3-Clause) |
| **GFS/FV3** | NOAA Global Forecast System with GFDL FV3 dynamical core | https://www.emc.ncep.noaa.gov/ | Open-source | Verified (unspecified) | Open-source verified |
| **ECMWF IFS** | Integrated Forecasting System — world-leading operational NWP | https://www.ecmwf.int/ | Restricted | N/A | Not open-source / restricted |
| **CLM** | Community Land Model — land-surface component of CESM | https://www.cesm.ucar.edu/models/clm | Open-source | Verified (unspecified) | Open-source verified |
| **POP** | Parallel Ocean Program (LANL) — ocean component of CESM | https://github.com/ESCOMP/POP2-CESM | Unclear | Unknown | No explicit OSS license in repo; see [POP source](https://github.com/ESCOMP/POP2-CESM) and [CESM license table entry](https://github.com/ESCOMP/CESM/blob/cesm3.0-alphabranch/LICENSE.txt) |
| **CICE** | Los Alamos Sea Ice Model — used in CESM and many coupled systems | https://github.com/CICE-Consortium/CICE | Open-source | Verified (unspecified) | Open-source verified |
| **MODFLOW 6** | USGS modular groundwater flow simulation (object-oriented Fortran 2008) | https://github.com/MODFLOW-ORG/modflow6 | Open-source | Verified (unspecified) | Open-source verified |
| **PFLOTRAN** | Massively parallel subsurface flow and reactive transport (Fortran 2003/2008) | https://pflotran.org/ | Open-source | Verified (unspecified) | Open-source verified |
| **MITgcm** | MIT General Circulation Model — versatile non-hydrostatic model for ocean, atmosphere, and climate with adjoint capabilities | https://github.com/MITgcm | Open-source | Verified (unspecified) | Open-source verified |
| **WAVEWATCH III** | NOAA third-generation spectral wave model for operational wave forecasting (5D: space, time, spectrum) | https://github.com/NOAA-EMC/WW3 | Open-source | Verified (unspecified) | Open-source verified |
| **GOTM** | General Ocean Turbulence Model — 1D water column model with state-of-the-art turbulence parameterizations | https://github.com/gotm-model/code | Open-source | GPL | Open-source (GPL) |
| **GEOS-Chem** | Global 3D atmospheric chemistry model driven by NASA GEOS meteorological data | https://github.com/geoschem/geos-chem | Open-source | MIT | Open-source (MIT) |
| **CMAQ** | Community Multiscale Air Quality Model (US EPA) — ozone, particulates, toxics, and deposition | https://github.com/USEPA/CMAQ | Open-source | Verified (unspecified) | Open-source verified |
| **TIEGCM** | NCAR Thermosphere-Ionosphere-Electrodynamics General Circulation Model — first-principles upper-atmosphere model | https://www.hao.ucar.edu/modeling/tgcm/tie.php | Open-source | Verified (unspecified) | Open-source verified |
| **WRF-Hydro / NWM** | Community hydrologic modeling system; a configuration serves as the NOAA National Water Model | https://github.com/NCAR/wrf_hydro_nwm_public | Open-source | Verified (unspecified) | Open-source verified |

---

## 3. Earth Science & Geophysics

### Seismology & Solid Earth Geophysics

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **SEISMIC_CPML** | 16 Fortran 90 programs for 2D/3D elastic, viscoelastic, and poroelastic wave propagation with PML boundaries | https://github.com/geodynamics/seismic_cpml | Open-source | CIG | Open-source (CIG) |
| **AxiSEM** | Parallel spectral-element method for 3D wave propagation in axisymmetric spherical structures | https://github.com/geodynamics/axisem | Open-source | GPL | Open-source (GPL) |
| **SW4** | Seismic Waves 4th order — 3D seismic modeling with free surface and absorbing super-grid conditions | https://github.com/geodynamics/sw4 | Open-source | CIG | Open-source (CIG); mixed Fortran + C++ |
| **OpenSWPC** | Seismic wave propagation by parallel finite difference for 3D heterogeneous viscoelastic media (Fortran 2003) | https://github.com/OpenSWPC/OpenSWPC | Open-source | MIT | Open-source (MIT) |
| **GEMINI** | Green's functions and surface wave modes for elastic waves in 1D depth-dependent media | https://github.com/seismology-RUB/GEMINI | Open-source | Verified (unspecified) | Open-source verified |

### Land Surface Models & Terrestrial Ecosystems

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **ORCHIDEE** | IPSL land surface model — terrestrial carbon, energy, water cycles, vegetation dynamics, and soil carbon (Fortran 90) | https://forge.ipsl.jussieu.fr/orchidee | Open-source | CeCILL | Open-source (CeCILL) |
| **JULES** | Joint UK Land Environment Simulator — Met Office community land surface model for climate and NWP | https://jules-lsm.github.io | Open-source | Verified (unspecified) | Open-source verified; requires MOSRS registration |
| **Noah-MP** | Noah with Multi-Parameterization — modular land surface model used in WRF, CESM, and NOAA NWM | https://github.com/NCAR/noahmp | Open-source | Verified (unspecified) | Open-source verified |
| **CABLE** | Community Atmosphere Biosphere Land Exchange — Australian LSM for the ACCESS climate model (CSIRO) | https://github.com/CABLE-LSM/CABLE | Open-source | BSD/MIT modified | Open-source (CSIRO BSD/MIT modified) |
| **SURFEX/ISBA** | Meteo-France surface modeling platform including ISBA land scheme and Crocus snowpack model | https://www.umr-cnrm.fr/surfex/ | Open-source | CeCILL-C | Open-source (CeCILL-C) |
| **CLASSIC** | Canadian Land Surface Scheme including Biogeochemical Cycles — successor to CLASS/CTEM (Modern Fortran) | https://cccma.gitlab.io/classic_pages/ | Open-source | Verified (unspecified) | Open-source verified |
| **ELM** | E3SM Land Model — DOE land component derived from CLM4.5 with phosphorus cycle and microbial dynamics | https://github.com/E3SM-Project/E3SM | Open-source | BSD-3-Clause | Open-source (BSD-3-Clause) |
| **Simsphere** | 1D SVAT model simulating heat and moisture transfer between plants, soil, and atmosphere (Penn State) | https://github.com/simsphere/simsphere | Open-source | Verified (unspecified) | Open-source verified |

> **Note:** BEPS (Biosphere-atmosphere Exchange Process Simulator) is a related ecosystem model for carbon/water/energy fluxes, but is implemented in C, not Fortran. See https://github.com/JChen-UToronto/BEPS_hourly_site.

### Dynamic Global Vegetation Models

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **LPJ-LMfire** | DGVM with fire dynamics and biomass burning — vegetation establishment, growth, and competition | https://github.com/ARVE-Research/LPJ-LMfire | Open-source | Verified (unspecified) | Open-source verified |
| **SEIB-DGVM** | Spatially Explicit Individual-Based DGVM — simulates vegetation in 30m x 30m virtual forests | https://seib-dgvm.com | Open-source | Verified (unspecified) | Open-source verified |
| **JeDi-DGVM** | Jena Diversity DGVM — focusing on plant functional diversity | https://github.com/ryanpavlick/JeDi-DGVM | Open-source | Verified (unspecified) | Open-source verified |
| **SDGVM / SOUP** | Sheffield Dynamic Global Vegetation Model — cohort-based DGVM (Fortran 2003) | https://github.com/marklomas60/SOUP | Open-source | Verified (unspecified) | Open-source verified |
| **VOM** | Vegetation Optimality Model — predicts vegetation water use without site-specific calibration | https://github.com/schymans/VOM | Open-source | Verified (unspecified) | Open-source verified |

### Hydrology & Watershed Modeling

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **SWAT+** | Soil and Water Assessment Tool Plus — watershed model for hydrology, water quality, and land management (USDA-ARS / Texas A&M) | https://github.com/swat-model/swatplus | Open-source | Verified (unspecified) | Open-source verified |
| **PRMS** | USGS Precipitation Runoff Modeling System — distributed-parameter watershed hydrology model | https://github.com/nhm-usgs/prms | Open-source | Public domain (USGS) | Public domain (USGS) |
| **SUMMA** | Structure for Unifying Multiple Modeling Alternatives — NCAR hydrologic modeling framework with multiple model structure options | https://github.com/NCAR/summa | Open-source | GPL-3.0 | Open-source (GPL-3.0) |
| **SMASH** | Spatially distributed Modeling and ASsimilation for Hydrology — Fortran engine with Python interface | https://github.com/DassHydro/smash | Open-source | Verified (unspecified) | Open-source verified |
| **TOPMODEL** | Topography-based hydrological model with NOAA BMI interface (Fortran, Keith Beven 1995) | https://github.com/NOAA-OWP/topmodel | Open-source | Verified (unspecified) | Open-source verified |

### Coastal, Tsunami & Ocean Wave Modeling

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **GeoClaw** | Clawpack module for geophysical flows — tsunami, storm surge, and overland flooding with AMR | https://github.com/clawpack/geoclaw | Open-source | BSD | Open-source (BSD) |
| **ADCIRC** | Advanced Circulation — finite element storm surge, tidal, and wind-driven circulation on unstructured grids | https://github.com/adcirc/adcirc | Open-source | Verified (unspecified) | Open-source verified |
| **SCHISM** | Semi-implicit Cross-scale Hydroscience Integrated System Model — unstructured-grid 3D baroclinic creek-to-ocean model | https://github.com/schism-dev/schism | Open-source | Apache-2.0 | Open-source (Apache-2.0) |
| **OceanWave3D** | Simulation of nonlinear and dispersive free surface waves in varying bathymetries | https://github.com/apengsigkarup/OceanWave3D-Fortran90 | Open-source | GPL | Open-source (GPL) |
| **TELEMAC-MASCARET** | Suite for 2D/3D free-surface hydraulics, sediment transport, and wave modeling (EDF, France) | https://www.opentelemac.org/ | Open-source | GPL-3.0 | Open-source (GPL-3.0) |
| **Clawpack / AMRClaw** | Conservation Laws Package — AMR for hyperbolic PDEs with Fortran Riemann solvers | https://github.com/clawpack | Open-source | BSD | Open-source (BSD) |
| **SWAN** | Simulating Waves Nearshore — third-generation wave model for coastal regions (Delft University) | https://swanmodel.sourceforge.io/ | Open-source | Verified (unspecified) | Open-source verified |
| **Delft3D** | 2D/3D modeling suite for hydrodynamics, sediment transport, morphology, and water quality | https://oss.deltares.nl/web/delft3d | Open-source | LGPL | Open-source (LGPL); mixed Fortran + C++ |
| **XBeach** | Hydrodynamic and morphodynamic processes on sandy coasts — dune erosion and breaching | https://github.com/openearth/xbeach | Open-source | Verified (unspecified) | Open-source verified |

### River Routing & Flood Modeling

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **mizuRoute** | NCAR reach-based river routing — impulse response, kinematic wave, diffusive wave methods | https://github.com/ESCOMP/mizuRoute | Open-source | Verified (unspecified) | Open-source verified |
| **CaMa-Flood** | Catchment-based Macro-scale Floodplain model — global river hydrodynamics with floodplain storage | https://github.com/global-hydrodynamics/CaMa-Flood_v4 | Open-source | Apache-2.0 | Open-source (Apache-2.0) |
| **RAPID** | Routing Application for Parallel computatIon of Discharge — large river network routing | https://github.com/c-h-david/rapid | Open-source | Verified (unspecified) | Open-source verified |
| **LISFLOOD-FP** | 2D hydrodynamic model for floodplain inundation on regular grids (University of Bristol) | https://github.com/openearth/lisflood-fp-bmi | Open-source | Verified (unspecified) | Open-source verified; mixed Fortran + C++ |

### Sediment Transport & Geomorphology

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **FastScapeLib** | Efficient O(n) algorithms for landscape evolution — stream power law, hillslope diffusion | https://github.com/fastscape-lem/fastscapelib-fortran | Open-source | Verified (unspecified) | Open-source verified |
| **WASA-SED** | Hydrological and sediment flux simulation for meso-scale catchments | https://github.com/TillF/WASA-SED | Open-source | Verified (unspecified) | Open-source verified |
| **WEPP** | USDA Water Erosion Prediction Project — process-based soil erosion model | https://www.ars.usda.gov/midwest-area/west-lafayette-in/national-soil-erosion-research/docs/wepp/ | Open-source | Verified (unspecified) | Open-source verified |

### Atmospheric Chemistry & Air Quality

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **EMEP/MSC-W** | European air quality model for acidifying/eutrophying pollutants, photo-oxidants, and PM (Norwegian Met Institute) | https://github.com/metno/emep-ctm | Open-source | Verified (unspecified) | Open-source verified |
| **AtChem2** | Atmospheric chemistry box-model for the Master Chemical Mechanism (MCM) gas-phase oxidation | https://github.com/AtChem/AtChem2 | Open-source | MIT | Open-source (MIT) |
| **DSMACC** | Dynamically Simple Model of Atmospheric Chemical Complexity — tropospheric chemistry box model | https://github.com/barronh/DSMACC | Open-source | Verified (unspecified) | Open-source verified |

### Geodesy & Gravity

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **SHTOOLS** | Spherical Harmonic Tools — Fortran 95/Python for spherical harmonic transforms, gravity and magnetic field analysis | https://github.com/SHTOOLS/SHTOOLS | Open-source | BSD-3-Clause | Open-source (BSD-3-Clause) |
| **GeographicLib-Fortran** | Fortran implementation of geodesic routines for solving geodesic problems on an ellipsoid | https://github.com/geographiclib/geographiclib-fortran | Open-source | MIT | Open-source (MIT) |
| **Fortran-Astrodynamics-Toolkit** | Modern Fortran library with geodesy, gravity field evaluation, and coordinate transformations | https://github.com/jacobwilliams/Fortran-Astrodynamics-Toolkit | Open-source | BSD-3-Clause | Open-source (BSD-3-Clause) |

### Geodynamics & Mantle Convection

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **CitcomS** | Finite element thermochemical convection in Earth's mantle in spherical shell geometry | https://github.com/geodynamics/citcoms | Open-source | GPL | Open-source (GPL); mixed C + Fortran |
| **ECOMAN** | Geodynamic and seismological modeling of mechanical anisotropy in mantle aggregates (OpenMP) | https://github.com/mfaccenda/ECOMAN2.0-geodynamics | Open-source | Verified (unspecified) | Open-source verified |
| **LaMEM** | Lithosphere and Mantle Evolution Model — parallel 3D thermo-mechanical geodynamics on PETSc | https://github.com/UniMainzGeo/LaMEM | Open-source | Verified (unspecified) | Open-source verified; mixed C + Fortran |

### Glaciology & Ice Sheet Modeling

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **CISM** | Community Ice Sheet Model — next-generation model for ice sheet evolution and sea level rise | https://github.com/CISM/cism | Open-source | LGPL | Open-source (LGPL) |
| **PISM** | Parallel Ice Sheet Model — framework for thermodynamically coupled ice sheets and glaciers | https://github.com/pism/pism | Open-source | GPL-3.0 | Open-source (GPL-3.0); mixed C++ + Fortran |
| **Elmer/Ice** | Full-Stokes finite element ice sheet/flow model, add-on to Elmer multiphysics suite | https://elmerice.elmerfem.org/ | Open-source | GPL | Open-source (GPL); see also Elmer in Section 8 |

### Space Weather & Ionosphere

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **GITM** | Global Ionosphere/Thermosphere Model — 3D coupled ionosphere-thermosphere system (Fortran 90) | https://github.com/GITMCode/GITM | Open-source | Verified (unspecified) | Open-source verified |
| **SWMF** | Space Weather Modeling Framework — modular system coupling solar corona through radiation belt (~700K lines Fortran) | https://github.com/MSTEM-QUDA | Open-source | Apache-2.0 | Open-source (Apache-2.0) |
| **IRI** | International Reference Ionosphere — empirical standard model of the ionosphere (Fortran core with Python/Matlab wrappers) | https://github.com/space-physics/iri2020 | Open-source | Verified (unspecified) | Open-source verified |
| **IRBEM** | International Radiation Belt Environment Modeling — magnetic coordinates, geophysics model evaluation | https://github.com/PRBEM/IRBEM | Open-source | Verified (unspecified) | Open-source verified |
| **EPOCH** | Particle-in-cell code for plasma physics applicable to space weather and laser-plasma interaction | https://github.com/epochpic/epoch | Open-source | GPL-3.0 | Open-source (GPL-3.0) |

### Volcanic Modeling & Ash Transport

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **FALL3D** | Eulerian model for atmospheric transport and deposition of volcanic particles, aerosols, and radionuclides | https://fall3d-suite.gitlab.io/ | Open-source | Verified (unspecified) | Open-source verified |
| **PLUME-MoM-TSM** | Steady-state integral volcanic plume model with two-size moment method for grain-size distribution | https://github.com/demichie/PLUME-MoM-TSM | Open-source | Verified (unspecified) | Open-source verified |
| **Ash3d** | USGS volcanic ash transport and dispersion model with MetReader and Projection libraries | https://github.com/DOI-USGS/volcano-ash3d-metreader | Open-source | Public domain (USGS) | Public domain (USGS) |

### Radiative Transfer

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **LBLRTM** | Line-By-Line Radiative Transfer Model — accurate UV to sub-millimeter, derived from FASCODE (AER) | https://github.com/AER-RC/LBLRTM | Open-source | Verified (unspecified) | Open-source verified |
| **SBDART** | Santa Barbara DISORT Atmospheric Radiative Transfer — plane-parallel model based on DISORT + LOWTRAN | https://github.com/paulricchiazzi/SBDART | Open-source | Verified (unspecified) | Open-source verified |
| **NEMESIS** | General-purpose radiative transfer and retrieval for visible/infrared observations of any planetary atmosphere | https://nemesiscode.github.io/ | Open-source | Verified (unspecified) | Open-source verified |
| **DMRT-ML** | Dense Media Radiative Transfer Multi-Layers — microwave emission from snowpack | https://github.com/ghislainp/dmrtml | Open-source | Verified (unspecified) | Open-source verified |
| **ecRad** | ECMWF atmospheric radiation scheme including RRTMG and ecCKD (Fortran 2003) | https://github.com/ecmwf-ifs/ecrad | Open-source | Apache-2.0 | Open-source (Apache-2.0) |
| **SOCRATES** | UK Met Office Suite Of Community RAdiative Transfer codes (Edwards & Slingo) | https://github.com/FormingWorlds/SOCRATES | Open-source | Verified (unspecified) | Open-source verified |
| **SPARTACUS-Surface** | ECMWF radiative transfer in complex 3D surface canopies — forests and cities | https://github.com/ecmwf/spartacus-surface | Open-source | Verified (unspecified) | Open-source verified |
| **libRadtran** | Library for solar and thermal radiation calculations in the Earth's atmosphere | https://www.libradtran.org/ | Open-source | GPL | Open-source (GPL); mixed C + Fortran |
| **DISORT** | DIScrete Ordinate Radiative Transfer — foundational solver for scattering/emitting layered media | Included in libRadtran | Open-source | Verified (unspecified) | Open-source verified |

### Snow & Permafrost Models

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **FSM2** | Flexible Snow Model — multi-physics energy balance model of snow on ground and in forest canopies | https://github.com/RichardEssery/FSM2 | Open-source | Verified (unspecified) | Open-source verified |
| **Crocus** | Detailed snowpack model for snow metamorphism and layered properties — embedded in SURFEX/ISBA | https://www.umr-cnrm.fr/surfex/ | Open-source | CeCILL-C | Open-source (CeCILL-C); part of SURFEX |
| **UEB** | Utah Energy Balance snowmelt model (Utah State University) | https://github.com/dtarb/UEB | Open-source | Verified (unspecified) | Open-source verified |
| **Parallel-SnowModel** | Parallelized SnowModel using Coarray Fortran (NCAR) | https://github.com/NCAR/Parallel-SnowModel | Open-source | Verified (unspecified) | Open-source verified |
| **GIPL** | Geophysical Institute Permafrost Laboratory model — phase changes in non-homogeneous soil (UAF) | https://github.com/Elchin/GIPL | Open-source | Verified (unspecified) | Open-source verified |

### Soil, Agriculture & Environmental Hazards

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **DSSAT** | Decision Support System for Agrotechnology Transfer — cropping system model for 45+ crops | https://github.com/DSSAT/dssat-csm-os | Open-source | BSD-3-Clause | Open-source (BSD-3-Clause) |
| **WOFOST** | WOrld FOod STudies — crop simulation under various environmental and management conditions | https://github.com/ajwdewit/WOFOST | Open-source | Verified (unspecified) | Open-source verified |
| **plantFEM** | Plant/farming simulator based on Finite Element Method for crops and soil foundations (Fortran 2003) | https://github.com/kazulagi/plantFEM | Open-source | Verified (unspecified) | Open-source verified |
| **FDS** | Fire Dynamics Simulator — large-eddy simulation for smoke and heat transport from fires (NIST, Fortran 2018) | https://github.com/firemodels/fds | Open-source | Public domain (NIST) | Public domain (NIST) |
| **CFAST** | Consolidated Model of Fire and Smoke Transport — two-zone fire model for compartmented structures (NIST) | https://github.com/firemodels/cfast | Open-source | Verified (unspecified) | Open-source verified |
| **ELMFIRE** | Eulerian Level Set Model of FIRE spread — operational wildland fire spread model | https://github.com/lautenberger/elmfire | Open-source | EPL-2.0 | Open-source (EPL-2.0) |
| **SWAP** | Soil Water Atmosphere Plant — agro-/ecohydrological model from Wageningen University | https://github.com/SWAP-model/ | Open-source | Verified (unspecified) | Open-source verified |

### Nuclear & Particle Physics

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **OpenMC** | Community Monte Carlo neutron and photon transport — k-eigenvalue and fixed source (Fortran 2008) | https://github.com/openmc-dev/openmc | Open-source | MIT | Open-source (MIT) |
| **NJOY2016** | Nuclear data processing system — converts ENDF-format data for reactor analysis (LANL/Sandia) | https://github.com/njoy/NJOY2016 | Open-source | BSD-3-Clause | Open-source (BSD-3-Clause) |
| **DRAGON** | Lattice physics code for neutron behavior in nuclear reactor fuel assemblies | https://github.com/Ahmed-Naceur/dragon5 | Open-source | Verified (unspecified) | Open-source verified |

### Geothermal & Reservoir Simulation

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **Waiwera** | Parallel geothermal flow simulator with PETSc — phase transitions, fractured media (Fortran 2003) | https://github.com/waiwera/waiwera | Open-source | LGPL-3.0 | Open-source (LGPL-3.0) |
| **TOUGH2** | Multi-dimensional simulator for coupled transport of water, vapor, gas, and heat in porous media (LBNL) | https://tough.lbl.gov/ | Restricted | N/A | Not open-source / restricted |

### Electromagnetics

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **NEC2** | Numerical Electromagnetics Code — moment method for wire/surface antenna analysis (LLNL) | https://github.com/flintoftid/aegnec2 | Open-source | Public domain | Public domain (US Government) |

---

## 4. GFDL Ecosystem (NOAA)

### Core Model Components

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **MOM6** | Modular Ocean Model v6 — ALE algorithm on horizontal C-grid | https://github.com/NOAA-GFDL/MOM6 | Open-source | Verified (unspecified) | Open-source verified |
| **FMS** | Flexible Modeling System — framework for atmosphere/ocean/climate models | https://github.com/NOAA-GFDL/FMS | Open-source | Verified (unspecified) | Open-source verified |
| **SIS2** | Sea Ice Simulator v2 — dynamics, thermodynamics, coupling to ocean/atmosphere | https://github.com/NOAA-GFDL/SIS2 | Open-source | LGPL | Open-source (LGPL) |
| **GFDL_atmos_cubed_sphere** | FV3 dynamical core — atmospheric core for all GFDL weather/climate models | https://github.com/NOAA-GFDL/GFDL_atmos_cubed_sphere | Open-source | Verified (unspecified) | Open-source verified |
| **SHiELD_physics** | Physical parameterizations for the SHiELD atmosphere model | https://github.com/NOAA-GFDL/SHiELD_physics | Open-source | Verified (unspecified) | Open-source verified |
| **lm4** | GFDL Land Model v4 — vegetation, hydrology, land-atmosphere interaction | https://github.com/NOAA-GFDL/lm4 | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **atmos_phys** | GFDL unified atmospheric physical parameterizations | https://github.com/NOAA-GFDL/atmos_phys | Open-source | Verified (unspecified) | Open-source verified |
| **FMScoupler** | Coupler for component models on different grids via exchange grids | https://github.com/NOAA-GFDL/FMScoupler | Open-source | Verified (unspecified) | Open-source verified |
| **ocean_BGC** | Ocean biogeochemistry tracers (BLING, COBALT) for MOM5/MOM6 | https://github.com/NOAA-GFDL/ocean_BGC | Open-source | GPL header in [generic_abiotic.F90](https://github.com/NOAA-GFDL/ocean_BGC/blob/main/generic_tracers/generic_abiotic.F90) | Open-source (GPL header in [generic_abiotic.F90](https://github.com/NOAA-GFDL/ocean_BGC/blob/main/generic_tracers/generic_abiotic.F90)) |
| **ice_param** | Shared Fortran interfaces for GFDL ice models | https://github.com/NOAA-GFDL/ice_param | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **icebergs** | Iceberg calving, drift, and melting simulation | https://github.com/NOAA-GFDL/icebergs | Open-source | Verified (unspecified) | Open-source verified |
| **atmos_drivers** | Driver programs for FMS-enabled atmospheric dynamical cores | https://github.com/NOAA-GFDL/atmos_drivers | Open-source | Verified (unspecified) | Open-source verified |

### Radiation and Optics

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **rte-rrtmgp** | Radiative transfer solver + RRTMGP gas optics for planetary atmospheres | https://github.com/NOAA-GFDL/rte-rrtmgp | Open-source | BSD-3-Clause license | Open-source (BSD-3-Clause license) |
| **rte-ecckd** | ECCKD gas optics conforming to RTE-RRTMGP API | https://github.com/NOAA-GFDL/rte-ecckd | Unclear | Unknown | No explicit OSS license file found in [repo](https://github.com/NOAA-GFDL/rte-ecckd) |

### Coupled Model Configurations

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **AM4** | GFDL Atmosphere Model v4 (FV3 core + atmospheric physics) | https://github.com/NOAA-GFDL/AM4 | Unclear | GPL (header evidence) | No top-level license file; GPL header present in [src/ice_sis file](https://github.com/NOAA-GFDL/AM4/blob/main/src/ice_sis/combined_ice_ocean_driver.F90) |
| **CM4** | GFDL Coupled Climate Model v4 (atmosphere+ocean+ice+land) | https://github.com/NOAA-GFDL/CM4 | Unclear | Unknown | No explicit OSS license file found in [repo](https://github.com/NOAA-GFDL/CM4) |
| **ESM4** | GFDL Earth System Model v4.1 (full carbon cycle + biogeochemistry) | https://github.com/NOAA-GFDL/ESM4 | Unclear | GPL (header evidence) | No top-level license file; LGPL header in [run script](https://github.com/NOAA-GFDL/ESM4/blob/main/run/ESM4_run.sh) |
| **SM2** | Slab Ocean Model for rapid climate sensitivity experiments | https://github.com/NOAA-GFDL/SM2 | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **SHiELD_build** | Build system for SHiELD and FV3 solo_core weather models | https://github.com/NOAA-GFDL/SHiELD_build | Open-source | Verified (unspecified) | Open-source verified |
| **MOM6-examples** | Example configurations and regression tests for MOM6/SIS2 | https://github.com/NOAA-GFDL/MOM6-examples | Open-source | Verified (unspecified) | Open-source verified |

### Analysis and Diagnostic Tools

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **GFDL-VortexTracker** | Tropical cyclone tracking algorithm (operational since 1998) | https://github.com/NOAA-GFDL/GFDL-VortexTracker | Unclear | Unknown | No explicit OSS license file found in [repo](https://github.com/NOAA-GFDL/GFDL-VortexTracker) |
| **TCtracker** | Tropical cyclone tracker analysis tool | https://github.com/NOAA-GFDL/TCtracker | Open-source | GPL-2.0 license | Open-source (GPL-2.0 license) |
| **mocsy** | Ocean carbonate system thermodynamics (CO2, pH, alkalinity) | https://github.com/NOAA-GFDL/mocsy | Open-source | Verified (unspecified) | Open-source verified |
| **FRE-NCtools** | Grid/mosaic creation and netCDF manipulation for FMS models | https://github.com/NOAA-GFDL/FRE-NCtools | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |

### Null (Stub) Components

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **land_null** | Stub land component for running without active land model | https://github.com/NOAA-GFDL/land_null | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **atmos_null** | Stub atmosphere for ocean-ice configurations | https://github.com/NOAA-GFDL/atmos_null | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **ice_null** | Stub sea-ice component | https://github.com/NOAA-GFDL/ice_null | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **ocean_null** | Stub ocean for atmosphere-only configurations | https://github.com/NOAA-GFDL/ocean_null | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |

---

## 5. Computational Fluid Dynamics

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **Nek5000** | High-order spectral element CFD for incompressible flow (Argonne, Gordon Bell Prize) | https://github.com/Nek5000 | Open-source | BSD-3-Clause | Open-source (BSD-3-Clause) |
| **Neko** | Modern Fortran spectral element flow simulations (successor to Nek5000) | https://github.com/ExtremeFLOW/neko | Open-source | BSD | Open-source (BSD) |
| **CFL3D** | NASA structured-grid, cell-centered, upwind-biased RANS solver | https://github.com/nasa/CFL3D | Open-source | Apache-2.0 license | Open-source (Apache-2.0 license) |
| **FUN3D** | NASA unstructured-grid solver — incompressible to hypersonic | https://fun3d.larc.nasa.gov/ | Restricted | N/A | Not open-source / restricted |
| **OVERFLOW** | NASA overset structured-grid solver for complex aerodynamic configurations | https://overflow.larc.nasa.gov/ | Restricted | N/A | Not open-source / restricted |
| **Xcompact3d** | High-order finite-difference DNS/LES on Cartesian meshes | https://github.com/xcompact3d/Incompact3d | Open-source | BSD-3-Clause license | Open-source (BSD-3-Clause license) |
| **nekRS** | GPU-accelerated spectral element CFD (Nek5000 heritage) | https://github.com/Nek5000/nekRS | Open-source | Verified (unspecified) | Open-source verified |
| **DLR TAU** | DLR aerospace CFD — Euler/RANS on hybrid unstructured grids | https://www.dlr.de/ | Restricted | N/A | Not open-source / restricted |

---

## 6. Molecular Dynamics / Quantum Chemistry / Materials Science

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **VASP** | Vienna Ab initio Simulation Package — plane-wave DFT (commercial) | https://www.vasp.at/ | Restricted | N/A | Not open-source / restricted |
| **Quantum ESPRESSO** | Electronic-structure and materials modeling with plane waves and pseudopotentials | https://gitlab.com/QEF/q-e | Open-source | GPL-2.0 | Open-source (GPL-2.0) |
| **GAMESS** | General Atomic and Molecular Electronic Structure System (~750k lines Fortran) | https://www.msg.chem.iastate.edu/ | Restricted | N/A | Not open-source / restricted |
| **NWChem** | High-performance computational chemistry (PNNL) | https://github.com/nwchemgit/nwchem | Open-source | Verified (unspecified) | Open-source verified |
| **CP2K** | Quantum chemistry and solid-state physics (Fortran 2008) | https://github.com/cp2k/cp2k | Open-source | GPL-2.0 license | Open-source (GPL-2.0 license) |
| **ABINIT** | DFT for molecules and periodic solids | https://github.com/abinit/abinit | Open-source | GPL-3.0 | Open-source (GPL-3.0) |
| **SIESTA** | DFT with numerical atomic orbitals — thousands of atoms | https://github.com/siesta-project | Open-source | GPL-3.0 | Open-source (GPL-3.0) |
| **OpenMolcas** | Multiconfigurational quantum chemistry (CASSCF, CASPT2) | https://gitlab.com/Molcas/OpenMolcas | Open-source | LGPL-2.1 | Open-source (LGPL-2.1) |
| **MOLPRO** | Highly accurate electron correlation methods (commercial) | https://www.molpro.net/ | Restricted | N/A | Not open-source / restricted |
| **Tinker** | Molecular design with AMOEBA polarizable force fields (Fortran 95) | https://github.com/TinkerTools/tinker | Open-source | Verified (unspecified) | Open-source verified |
| **Tinker-HP** | Massively parallel Tinker for long polarizable MD (MPI + GPU) | https://github.com/TinkerTools/tinker-hp | Restricted | N/A | Not open-source/restricted; see [README license section](https://github.com/TinkerTools/tinker-hp/blob/master/README.md) and [license PDF](https://github.com/TinkerTools/tinker-hp/blob/master/license-Tinker.pdf) |
| **DL_POLY** | General-purpose classical molecular dynamics (Daresbury Lab) | https://github.com/ccp5UK/dl-poly | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **CASTEP** | Plane-wave pseudopotential DFT for solid-state materials | http://www.castep.org/ | Restricted | N/A | Not open-source / restricted |
| **CRYSTAL** | Ab initio for crystalline solids with Gaussian basis sets | https://www.crystal.unito.it/ | Restricted | N/A | Not open-source / restricted |
| **TURBOMOLE** | Ab initio electronic structure calculations (commercial) | https://www.turbomole.org/ | Restricted | N/A | Not open-source / restricted |
| **GPAW** | DFT with projector-augmented wave method (Fortran/C/Python) | https://wiki.fysik.dtu.dk/gpaw/ | Open-source | Verified (unspecified) | Open-source verified |

---

## 7. Astrophysics / Space Science

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **MESA** | Modules for Experiments in Stellar Astrophysics — 1D stellar evolution | https://github.com/MESAHub/mesa | Open-source | LGPL-3.0 license | Open-source (LGPL-3.0 license) |
| **FLASH / FLASH-X** | Multi-physics AMR for astrophysical thermonuclear flashes and HEDP | https://flash.rochester.edu/ | Restricted | Mixed/restricted | Mixed/restricted: [FLASH software terms](https://flash.rochester.edu/site/flashcode/user_support/flash_ug_devel/node184.html), [FLASH code request](https://flash.rochester.edu/site/flashcode/), [Flash-X Apache-2.0 but access-controlled source](https://flash-x.org/index.php/source-code/) |
| **Phantom** | Fast parallel SPH and MHD for astrophysics (modern Fortran) | https://github.com/danieljprice/phantom | Open-source | Verified (unspecified) | Open-source verified |
| **RAMSES** | AMR for self-gravitating, magnetized, compressible radiative fluid flows (F90 + MPI) | https://github.com/ramses-organisation/ramses | Open-source | [CeCILL license](https://github.com/ramses-organisation/ramses/blob/dev/doc/license.txt) | Open-source ([CeCILL license](https://github.com/ramses-organisation/ramses/blob/dev/doc/license.txt)) |
| **SPECFEM3D** | Spectral-element seismic wave propagation at local/regional scales | https://github.com/SPECFEM | Open-source | GPL-3.0 | Open-source (GPL-3.0) |
| **SPECFEM3D_GLOBE** | Global-scale full-waveform seismic simulations (Earth, Mars, Moon) | https://github.com/SPECFEM/specfem3d_globe | Open-source | GPL-3.0 license | Open-source (GPL-3.0 license) |
| **CASTRO** | AMReX-based compressible astrophysical hydrodynamics (Fortran physics kernels) | https://github.com/AMReX-Astro/Castro | Open-source | BSD-style [license.txt](https://github.com/AMReX-Astro/Castro/blob/main/license.txt) | Open-source (BSD-style [license.txt](https://github.com/AMReX-Astro/Castro/blob/main/license.txt)) |

---

## 8. Finite Element / Structural Analysis

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **CalculiX** | 3D structural FEA — Abaqus-compatible, nonlinear thermal/mechanical | https://www.calculix.de/ | Open-source | Verified (unspecified) | Open-source verified |
| **Code_Aster** | Thermo-mechanical FEA with fracture analysis (EDF, France) | https://gitlab.com/codeaster/src | Open-source | GPL-3.0 | Open-source (GPL-3.0) |
| **Elmer** | Multiphysics FEM — heat, EM, fluids, structures (CSC Finland) | https://github.com/ElmerCSC/elmerfem | Open-source | Verified (unspecified) | Open-source verified |
| **NASTRAN-95** | NASA's original FEA program (public domain) | https://github.com/nasa/NASTRAN-95 | Open-source | [NASA Open Source Agreement v1.3](https://github.com/nasa/NASTRAN-95/blob/master/NASA%20Open%20Source%20Agreement-NASTRAN%2095.doc) | Open-source ([NASA Open Source Agreement v1.3](https://github.com/nasa/NASTRAN-95/blob/master/NASA%20Open%20Source%20Agreement-NASTRAN%2095.doc)) |
| **MYSTRAN** | Modern Fortran 95 linear structural FEA (NASTRAN-compatible input) | https://github.com/MYSTRANsolver/MYSTRAN | Open-source | MIT license | Open-source (MIT license) |
| **FEAPpv** | General-purpose FEA for research and education | https://github.com/sanjayg0/feappv | Open-source | BSD-3-Clause license | Open-source (BSD-3-Clause license) |

---

## 9. Optimization & Mathematical Libraries

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **MINPACK** | Nonlinear equations and least-squares minimization | https://github.com/fortran-lang/minpack | Open-source | Verified (unspecified) | Open-source verified |
| **ODEPACK** | ODE solvers for stiff and non-stiff initial-value problems | https://www.netlib.org/odepack/ | Open-source | Verified (unspecified) | Open-source verified |
| **FFTPACK** | Fast Fourier transforms for periodic and symmetric sequences (NCAR) | https://github.com/fortran-lang/fftpack | Open-source | Verified (unspecified) | Open-source verified |
| **modern_fftpack** | Object-oriented Fortran 2008 modernization of FFTPACK5.1 | https://github.com/jlokimlin/modern_fftpack | Open-source | Verified (unspecified) | Open-source verified |
| **QUADPACK** | Adaptive numerical integration of 1D functions | https://github.com/jacobwilliams/quadpack | Open-source | Verified (unspecified) | Open-source verified |
| **FITPACK** | Curve and surface fitting with splines | https://www.netlib.org/fitpack/ | Open-source | Verified (unspecified) | Open-source verified |
| **L-BFGS-B** | Limited-memory BFGS for large-scale bound-constrained optimization | https://users.iems.northwestern.edu/~nocedal/lbfgsb.html | Open-source | Verified (unspecified) | Open-source verified |
| **SLATEC** | 1,400+ math/statistics routines (BLAS, LINPACK, QUADPACK, FFTPACK, EISPACK) | https://www.netlib.org/slatec/ | Open-source | Verified (unspecified) | Open-source verified |
| **NAG Library** | Largest collection of robust numerical algorithms for Fortran (commercial) | https://www.nag.com/content/nag-library | Restricted | N/A | Not open-source / restricted |
| **IMSL Fortran** | Comprehensive math/statistics library (commercial, 50+ years) | https://www.imsl.com/products/imsl-fortran-libraries | Restricted | N/A | Not open-source / restricted |
| **NLopt** | Nonlinear optimization with Fortran bindings (global + local algorithms) | https://github.com/stevengj/nlopt | Open-source | LGPL | Open-source (LGPL) |

---

## 10. General Fortran Libraries & Frameworks

| Package | Description | Source | Open-Source Status | License | Notes |
|---------|-------------|--------|--------------------|---------|-------|
| **stdlib** | Community Fortran Standard Library — algorithms, data structures, math utilities | https://github.com/fortran-lang/stdlib | Open-source | MIT license | Open-source (MIT license) |
| **fpm** | Fortran Package Manager — official build system for modern Fortran | https://github.com/fortran-lang/fpm | Open-source | MIT license | Open-source (MIT license) |
| **FORD** | FORtran Documenter — automatic API documentation generator | https://github.com/cmacmackin/ford | Open-source | GPL-3.0 license | Open-source (GPL-3.0 license) |
| **json-fortran** | Thread-safe, object-oriented JSON API (Fortran 2008) | https://github.com/jacobwilliams/json-fortran | Open-source | Verified (unspecified) | Open-source verified |
| **h5fortran** | Lightweight, polymorphic HDF5 interface for Fortran | https://github.com/geospace-code/h5fortran | Open-source | BSD-3-Clause license | Open-source (BSD-3-Clause license) |
| **nc4fortran** | Object-oriented NetCDF4 interface (Fortran 2008) | https://github.com/geospace-code/nc4fortran | Open-source | MIT license | Open-source (MIT license) |
| **FLAP** | Fortran command Line Arguments Parser | https://github.com/szaghi/FLAP | Open-source | Verified (unspecified) | Open-source verified |
| **fypp** | Python-powered Fortran preprocessor (conditionals, loops, templates) | https://github.com/aradi/fypp | Open-source | BSD-2-Clause license | Open-source (BSD-2-Clause license) |
| **coretran** | Sorting, kD-Trees, dynamic arrays, and core data structures | https://github.com/leonfoks/coretran | Open-source | BSD-3-Clause license | Open-source (BSD-3-Clause license) |
| **pFUnit** | Unit testing framework for Fortran (supports MPI-parallel tests) | https://github.com/Goddard-Fortran-Ecosystem/pFUnit | Open-source | Verified (unspecified) | Open-source verified |
| **test-drive** | Lightweight procedural unit testing framework (fpm-compatible) | https://github.com/fortran-lang/test-drive | Open-source | Apache-2.0 license | Open-source (Apache-2.0 license) |
| **datetime-fortran** | Date and time manipulation (inspired by Python's datetime) | https://github.com/wavebitscientific/datetime-fortran | Open-source | MIT license | Open-source (MIT license) |

---

## References

- [Fortran-lang Community](https://fortran-lang.org/)
- [NOAA-GFDL GitHub Organization](https://github.com/NOAA-GFDL)
- [Netlib Repository](https://www.netlib.org/)
- [Fortran Wiki](https://fortranwiki.org/)
- [Awesome Fortran (GitHub)](https://github.com/rabbiabram/awesome-fortran)
- [Beliavsky's Fortran Code on GitHub](https://github.com/Beliavsky/Fortran-code-on-GitHub)
- [Computational Infrastructure for Geodynamics (CIG)](https://geodynamics.org/)
- [US EPA Environmental Modeling](https://www.epa.gov/computational-tools-and-databases)
- [USGS Software](https://www.usgs.gov/products/software)
- [NCAR Software](https://www.mmm.ucar.edu/models)
