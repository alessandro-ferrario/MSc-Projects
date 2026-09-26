# Computational Fluid Dynamics - Laboratory Projects

- **Course:** Computational Fluid Dynamics - Fundamentals | Politecnico di Milano
- **Instructors:** Prof. G. Montenegro, Prof. G.B.A. Persico
- **Academic Year:** 2024 - 2025

## Course Overview
This folder contains the numerical simulations, mesh sensitivity analyses, and fluid dynamics reports developed for the *Computational Fluid Dynamics* course using OpenFOAM. The activities focus on both internal (nozzle duct) and external (airfoil profile) aerodynamic flows, comparing laminar and turbulent regimes. Key emphasis is placed on numerical discretization schemes, boundary layer resolution, turbulence modeling selection, and grid independence studies.

---

## 🔬 Laboratory Activities & Projects

### 1. CFD Analysis of a 2D Converging-Diverging Nozzle
* **Goal:** Numerical simulation of internal 2D flow across laminar and turbulent regimes. Evaluates numerical schemes, boundary layer meshing, and grid convergence to extract wall shear stresses, flow rates, outlet velocity profiles, and static/total pressure drops.
* **Methods/Keywords:** Internal Flow, Laminar/Turbulent Regimes, k-omega SST, Wall Functions, y+ Sensitivity, Grid Independence Study.
* **Software:** OpenFOAM, ParaView, MATLAB

### 2. External Aerodynamic Analysis of a NACA 4412 Airfoil
* **Goal:** Simulation of external flow around a 2D NACA 4412 aerodynamic profile. Compares different RANS turbulence closures (Spalart-Allmaras vs. k-epsilon) with and without wall functions, evaluates wake velocity deficits downstream, and computes lift (C_L) and drag (C_D) polar characteristics.
* **Methods/Keywords:** External Aerodynamics, Airfoil Polar, Spalart-Allmaras (SA), k-epsilon, Wall Functions, Aerodynamic Coefficients (C_L, C_D), Wake.
* **Software:** OpenFOAM, ParaView, MATLAB
