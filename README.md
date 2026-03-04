# Scientific Computing Software Collection (Fortran)

A curated catalog of scientific computing software written in Fortran (77 through modern Fortran 2018), organized by domain.

---

## Table of Contents

1. [Numerical Linear Algebra](#1-numerical-linear-algebra)
2. [Climate, Ocean & Weather Modeling](#2-climate-ocean--weather-modeling)
3. [GFDL Ecosystem (NOAA)](#3-gfdl-ecosystem-noaa)
4. [Computational Fluid Dynamics](#4-computational-fluid-dynamics)
5. [Molecular Dynamics / Quantum Chemistry / Materials Science](#5-molecular-dynamics--quantum-chemistry--materials-science)
6. [Astrophysics / Space Science](#6-astrophysics--space-science)
7. [Finite Element / Structural Analysis](#7-finite-element--structural-analysis)
8. [Optimization & Mathematical Libraries](#8-optimization--mathematical-libraries)
9. [General Fortran Libraries & Frameworks](#9-general-fortran-libraries--frameworks)

---

## 1. Numerical Linear Algebra

| Package | Description | Link |
|---------|-------------|------|
| **BLAS** | Reference Basic Linear Algebra Subprograms for vector and matrix operations | https://www.netlib.org/blas/ |
| **LAPACK** | Linear Algebra PACKage — linear systems, eigenvalue problems, SVD (Fortran 90) | https://github.com/Reference-LAPACK/lapack |
| **ScaLAPACK** | Scalable LAPACK for distributed-memory parallel computers via MPI | https://www.netlib.org/scalapack/ |
| **ARPACK-NG** | Large-scale sparse eigenvalue problems via implicitly restarted Arnoldi method | https://github.com/opencollab/arpack-ng |
| **MUMPS** | MUltifrontal Massively Parallel Sparse direct solver (Fortran 95, MPI) | https://mumps-solver.org/ |
| **PARDISO** | Parallel direct sparse solver in Intel oneAPI MKL | https://www.intel.com/content/www/us/en/docs/onemkl/ |
| **LINPACK** | Classic library for linear equations and least-squares (predecessor to LAPACK) | https://www.netlib.org/linpack/ |
| **EISPACK** | Eigenvalue/eigenvector computation (predecessor to LAPACK) | https://www.netlib.org/eispack/ |
| **FEAST** | Eigenvalue solver based on accelerated subspace iteration within intervals | https://feast.ecs.umass.edu/ |
| **fortran-lapack** | Modern Fortran interface to LAPACK | https://github.com/perazz/fortran-lapack |
| **SparseKit** | Tool-kit for sparse matrix computations (format conversion, I/O, sorting) | https://www-users.cse.umn.edu/~saad/software/SPARSKIT/ |
| **PSBLAS** | Parallel Sparse BLAS for distributed-memory sparse operations | https://github.com/sfilippone/psblas3 |
| **MLD2P4** | Multilevel Domain Decomposition Parallel Preconditioners (Fortran 2003) | https://github.com/sfilippone/mld2p4-2 |

---

## 2. Climate, Ocean & Weather Modeling

| Package | Description | Link |
|---------|-------------|------|
| **WRF** | Weather Research and Forecasting model — most widely used mesoscale NWP system | https://github.com/wrf-model/WRF |
| **MPAS** | Model for Prediction Across Scales — unstructured-mesh atmosphere/ocean/sea-ice | https://github.com/MPAS-Dev/MPAS-Model |
| **CESM** | Community Earth System Model — fully-coupled global climate model (CAM+CLM+POP+CICE) | https://github.com/ESCOMP/CESM |
| **ROMS** | Regional Ocean Modeling System — free-surface terrain-following ocean model | https://github.com/myroms |
| **NEMO** | Nucleus for European Modelling of the Ocean (Fortran 2008) | https://forge.nemo-ocean.eu/nemo/nemo |
| **ICON** | ICOsahedral Non-hydrostatic model — unified weather/climate system (DWD + MPI-M) | https://code.mpimet.mpg.de/projects/iconpublic |
| **GFS/FV3** | NOAA Global Forecast System with GFDL FV3 dynamical core | https://www.emc.ncep.noaa.gov/ |
| **ECMWF IFS** | Integrated Forecasting System — world-leading operational NWP | https://www.ecmwf.int/ |
| **CLM** | Community Land Model — land-surface component of CESM | https://www.cesm.ucar.edu/models/clm |
| **POP** | Parallel Ocean Program (LANL) — ocean component of CESM | https://github.com/ESCOMP/POP2-CESM |
| **CICE** | Los Alamos Sea Ice Model — used in CESM and many coupled systems | https://github.com/CICE-Consortium/CICE |
| **MODFLOW 6** | USGS modular groundwater flow simulation (object-oriented Fortran 2008) | https://github.com/MODFLOW-ORG/modflow6 |
| **PFLOTRAN** | Massively parallel subsurface flow and reactive transport (Fortran 2003/2008) | https://pflotran.org/ |

---

## 3. GFDL Ecosystem (NOAA)

### Core Model Components

| Package | Description | Link |
|---------|-------------|------|
| **MOM6** | Modular Ocean Model v6 — ALE algorithm on horizontal C-grid | https://github.com/NOAA-GFDL/MOM6 |
| **FMS** | Flexible Modeling System — framework for atmosphere/ocean/climate models | https://github.com/NOAA-GFDL/FMS |
| **SIS2** | Sea Ice Simulator v2 — dynamics, thermodynamics, coupling to ocean/atmosphere | https://github.com/NOAA-GFDL/SIS2 |
| **GFDL_atmos_cubed_sphere** | FV3 dynamical core — atmospheric core for all GFDL weather/climate models | https://github.com/NOAA-GFDL/GFDL_atmos_cubed_sphere |
| **SHiELD_physics** | Physical parameterizations for the SHiELD atmosphere model | https://github.com/NOAA-GFDL/SHiELD_physics |
| **lm4** | GFDL Land Model v4 — vegetation, hydrology, land-atmosphere interaction | https://github.com/NOAA-GFDL/lm4 |
| **atmos_phys** | GFDL unified atmospheric physical parameterizations | https://github.com/NOAA-GFDL/atmos_phys |
| **FMScoupler** | Coupler for component models on different grids via exchange grids | https://github.com/NOAA-GFDL/FMScoupler |
| **ocean_BGC** | Ocean biogeochemistry tracers (BLING, COBALT) for MOM5/MOM6 | https://github.com/NOAA-GFDL/ocean_BGC |
| **ice_param** | Shared Fortran interfaces for GFDL ice models | https://github.com/NOAA-GFDL/ice_param |
| **icebergs** | Iceberg calving, drift, and melting simulation | https://github.com/NOAA-GFDL/icebergs |
| **atmos_drivers** | Driver programs for FMS-enabled atmospheric dynamical cores | https://github.com/NOAA-GFDL/atmos_drivers |

### Radiation and Optics

| Package | Description | Link |
|---------|-------------|------|
| **rte-rrtmgp** | Radiative transfer solver + RRTMGP gas optics for planetary atmospheres | https://github.com/NOAA-GFDL/rte-rrtmgp |
| **rte-ecckd** | ECCKD gas optics conforming to RTE-RRTMGP API | https://github.com/NOAA-GFDL/rte-ecckd |

### Coupled Model Configurations

| Package | Description | Link |
|---------|-------------|------|
| **AM4** | GFDL Atmosphere Model v4 (FV3 core + atmospheric physics) | https://github.com/NOAA-GFDL/AM4 |
| **CM4** | GFDL Coupled Climate Model v4 (atmosphere+ocean+ice+land) | https://github.com/NOAA-GFDL/CM4 |
| **ESM4** | GFDL Earth System Model v4.1 (full carbon cycle + biogeochemistry) | https://github.com/NOAA-GFDL/ESM4 |
| **SM2** | Slab Ocean Model for rapid climate sensitivity experiments | https://github.com/NOAA-GFDL/SM2 |
| **SHiELD_build** | Build system for SHiELD and FV3 solo_core weather models | https://github.com/NOAA-GFDL/SHiELD_build |
| **MOM6-examples** | Example configurations and regression tests for MOM6/SIS2 | https://github.com/NOAA-GFDL/MOM6-examples |

### Analysis and Diagnostic Tools

| Package | Description | Link |
|---------|-------------|------|
| **GFDL-VortexTracker** | Tropical cyclone tracking algorithm (operational since 1998) | https://github.com/NOAA-GFDL/GFDL-VortexTracker |
| **TCtracker** | Tropical cyclone tracker analysis tool | https://github.com/NOAA-GFDL/TCtracker |
| **mocsy** | Ocean carbonate system thermodynamics (CO2, pH, alkalinity) | https://github.com/NOAA-GFDL/mocsy |
| **FRE-NCtools** | Grid/mosaic creation and netCDF manipulation for FMS models | https://github.com/NOAA-GFDL/FRE-NCtools |

### Null (Stub) Components

| Package | Description | Link |
|---------|-------------|------|
| **land_null** | Stub land component for running without active land model | https://github.com/NOAA-GFDL/land_null |
| **atmos_null** | Stub atmosphere for ocean-ice configurations | https://github.com/NOAA-GFDL/atmos_null |
| **ice_null** | Stub sea-ice component | https://github.com/NOAA-GFDL/ice_null |
| **ocean_null** | Stub ocean for atmosphere-only configurations | https://github.com/NOAA-GFDL/ocean_null |

---

## 4. Computational Fluid Dynamics

| Package | Description | Link |
|---------|-------------|------|
| **Nek5000** | High-order spectral element CFD for incompressible flow (Argonne, Gordon Bell Prize) | https://github.com/Nek5000 |
| **Neko** | Modern Fortran spectral element flow simulations (successor to Nek5000) | https://github.com/ExtremeFLOW/neko |
| **CFL3D** | NASA structured-grid, cell-centered, upwind-biased RANS solver | https://github.com/nasa/CFL3D |
| **FUN3D** | NASA unstructured-grid solver — incompressible to hypersonic | https://fun3d.larc.nasa.gov/ |
| **OVERFLOW** | NASA overset structured-grid solver for complex aerodynamic configurations | https://overflow.larc.nasa.gov/ |
| **Xcompact3d** | High-order finite-difference DNS/LES on Cartesian meshes | https://github.com/xcompact3d/Incompact3d |
| **nekRS** | GPU-accelerated spectral element CFD (Nek5000 heritage) | https://github.com/Nek5000/nekRS |
| **DLR TAU** | DLR aerospace CFD — Euler/RANS on hybrid unstructured grids | https://www.dlr.de/ |

---

## 5. Molecular Dynamics / Quantum Chemistry / Materials Science

| Package | Description | Link |
|---------|-------------|------|
| **VASP** | Vienna Ab initio Simulation Package — plane-wave DFT (commercial) | https://www.vasp.at/ |
| **Quantum ESPRESSO** | Electronic-structure and materials modeling with plane waves and pseudopotentials | https://gitlab.com/QEF/q-e |
| **GAMESS** | General Atomic and Molecular Electronic Structure System (~750k lines Fortran) | https://www.msg.chem.iastate.edu/ |
| **NWChem** | High-performance computational chemistry (PNNL) | https://github.com/nwchemgit/nwchem |
| **CP2K** | Quantum chemistry and solid-state physics (Fortran 2008) | https://github.com/cp2k/cp2k |
| **ABINIT** | DFT for molecules and periodic solids | https://github.com/abinit/abinit |
| **SIESTA** | DFT with numerical atomic orbitals — thousands of atoms | https://github.com/siesta-project |
| **OpenMolcas** | Multiconfigurational quantum chemistry (CASSCF, CASPT2) | https://gitlab.com/Molcas/OpenMolcas |
| **MOLPRO** | Highly accurate electron correlation methods (commercial) | https://www.molpro.net/ |
| **Tinker** | Molecular design with AMOEBA polarizable force fields (Fortran 95) | https://github.com/TinkerTools/tinker |
| **Tinker-HP** | Massively parallel Tinker for long polarizable MD (MPI + GPU) | https://github.com/TinkerTools/tinker-hp |
| **DL_POLY** | General-purpose classical molecular dynamics (Daresbury Lab) | https://github.com/ccp5UK/dl-poly |
| **CASTEP** | Plane-wave pseudopotential DFT for solid-state materials | http://www.castep.org/ |
| **CRYSTAL** | Ab initio for crystalline solids with Gaussian basis sets | https://www.crystal.unito.it/ |
| **TURBOMOLE** | Ab initio electronic structure calculations (commercial) | https://www.turbomole.org/ |
| **GPAW** | DFT with projector-augmented wave method (Fortran/C/Python) | https://wiki.fysik.dtu.dk/gpaw/ |

---

## 6. Astrophysics / Space Science

| Package | Description | Link |
|---------|-------------|------|
| **MESA** | Modules for Experiments in Stellar Astrophysics — 1D stellar evolution | https://github.com/MESAHub/mesa |
| **FLASH / FLASH-X** | Multi-physics AMR for astrophysical thermonuclear flashes and HEDP | https://flash.rochester.edu/ |
| **Phantom** | Fast parallel SPH and MHD for astrophysics (modern Fortran) | https://github.com/danieljprice/phantom |
| **RAMSES** | AMR for self-gravitating, magnetized, compressible radiative fluid flows (F90 + MPI) | https://github.com/ramses-organisation/ramses |
| **SPECFEM3D** | Spectral-element seismic wave propagation at local/regional scales | https://github.com/SPECFEM |
| **SPECFEM3D_GLOBE** | Global-scale full-waveform seismic simulations (Earth, Mars, Moon) | https://github.com/SPECFEM/specfem3d_globe |
| **CASTRO** | AMReX-based compressible astrophysical hydrodynamics (Fortran physics kernels) | https://github.com/AMReX-Astro/Castro |

---

## 7. Finite Element / Structural Analysis

| Package | Description | Link |
|---------|-------------|------|
| **CalculiX** | 3D structural FEA — Abaqus-compatible, nonlinear thermal/mechanical | https://www.calculix.de/ |
| **Code_Aster** | Thermo-mechanical FEA with fracture analysis (EDF, France) | https://gitlab.com/codeaster/src |
| **Elmer** | Multiphysics FEM — heat, EM, fluids, structures (CSC Finland) | https://github.com/ElmerCSC/elmerfem |
| **NASTRAN-95** | NASA's original FEA program (public domain) | https://github.com/nasa/NASTRAN-95 |
| **MYSTRAN** | Modern Fortran 95 linear structural FEA (NASTRAN-compatible input) | https://github.com/MYSTRANsolver/MYSTRAN |
| **FEAPpv** | General-purpose FEA for research and education | https://github.com/sanjayg0/feappv |

---

## 8. Optimization & Mathematical Libraries

| Package | Description | Link |
|---------|-------------|------|
| **MINPACK** | Nonlinear equations and least-squares minimization | https://github.com/fortran-lang/minpack |
| **ODEPACK** | ODE solvers for stiff and non-stiff initial-value problems | https://www.netlib.org/odepack/ |
| **FFTPACK** | Fast Fourier transforms for periodic and symmetric sequences (NCAR) | https://github.com/fortran-lang/fftpack |
| **modern_fftpack** | Object-oriented Fortran 2008 modernization of FFTPACK5.1 | https://github.com/jlokimlin/modern_fftpack |
| **QUADPACK** | Adaptive numerical integration of 1D functions | https://github.com/jacobwilliams/quadpack |
| **FITPACK** | Curve and surface fitting with splines | https://www.netlib.org/fitpack/ |
| **L-BFGS-B** | Limited-memory BFGS for large-scale bound-constrained optimization | https://users.iems.northwestern.edu/~nocedal/lbfgsb.html |
| **SLATEC** | 1,400+ math/statistics routines (BLAS, LINPACK, QUADPACK, FFTPACK, EISPACK) | https://www.netlib.org/slatec/ |
| **NAG Library** | Largest collection of robust numerical algorithms for Fortran (commercial) | https://www.nag.com/content/nag-library |
| **IMSL Fortran** | Comprehensive math/statistics library (commercial, 50+ years) | https://www.imsl.com/products/imsl-fortran-libraries |
| **NLopt** | Nonlinear optimization with Fortran bindings (global + local algorithms) | https://github.com/stevengj/nlopt |

---

## 9. General Fortran Libraries & Frameworks

| Package | Description | Link |
|---------|-------------|------|
| **stdlib** | Community Fortran Standard Library — algorithms, data structures, math utilities | https://github.com/fortran-lang/stdlib |
| **fpm** | Fortran Package Manager — official build system for modern Fortran | https://github.com/fortran-lang/fpm |
| **FORD** | FORtran Documenter — automatic API documentation generator | https://github.com/cmacmackin/ford |
| **json-fortran** | Thread-safe, object-oriented JSON API (Fortran 2008) | https://github.com/jacobwilliams/json-fortran |
| **h5fortran** | Lightweight, polymorphic HDF5 interface for Fortran | https://github.com/geospace-code/h5fortran |
| **nc4fortran** | Object-oriented NetCDF4 interface (Fortran 2008) | https://github.com/geospace-code/nc4fortran |
| **FLAP** | Fortran command Line Arguments Parser | https://github.com/szaghi/FLAP |
| **fypp** | Python-powered Fortran preprocessor (conditionals, loops, templates) | https://github.com/aradi/fypp |
| **coretran** | Sorting, kD-Trees, dynamic arrays, and core data structures | https://github.com/leonfoks/coretran |
| **pFUnit** | Unit testing framework for Fortran (supports MPI-parallel tests) | https://github.com/Goddard-Fortran-Ecosystem/pFUnit |
| **test-drive** | Lightweight procedural unit testing framework (fpm-compatible) | https://github.com/fortran-lang/test-drive |
| **datetime-fortran** | Date and time manipulation (inspired by Python's datetime) | https://github.com/wavebitscientific/datetime-fortran |

---

## References

- [Fortran-lang Community](https://fortran-lang.org/)
- [NOAA-GFDL GitHub Organization](https://github.com/NOAA-GFDL)
- [Netlib Repository](https://www.netlib.org/)
- [Fortran Wiki](https://fortranwiki.org/)
- [Awesome Fortran (GitHub)](https://github.com/rabbiabram/awesome-fortran)
- [Beliavsky's Fortran Code on GitHub](https://github.com/Beliavsky/Fortran-code-on-GitHub)
