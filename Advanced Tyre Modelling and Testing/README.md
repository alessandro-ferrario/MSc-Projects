# Advanced Tire Modeling and Testing - Laboratory Projects

**Course:** Advanced Tire Modeling and Testing | Politecnico di Milano  
**Instructors:** Prof. E. Sabbioni, Dr. L. Maglia  
**Academic Year:** 2025 - 2026  

## Course Overview
This folder contains the numerical tire models, parameter identification routines, and vehicle handling simulations developed for the *Advanced Tire Modeling and Testing* course. The activities focus on non-linear tire behavior, transient contact dynamics via relaxation length, thermal modeling, and active control interaction (ABS). A major portion of the work is dedicated to characterizing semi-empirical Pacejka models from experimental drum test rig data using numerical optimization toolboxes.

---

## 🔬 Laboratory Activities & Projects

### 1. Tire Influences on Vehicle Handling Dynamics
* **Goal:** Investigate how variations in tire mechanical parameters (cornering stiffness, relaxation lengths) affect steady-state understeer/oversteer gradients and transient vehicle response using a 7-DOF double-track vehicle model during steering pad and sine sweep maneuvers.
* **Methods/Keywords:** 7-DOF Double-Track Model, Pacejka Magic Formula, Steady-State Handling, Understeer Gradient, Relaxation Length, Transient Response.
* **Software:** MATLAB, Simulink

### 2. Coupled Thermal-Mechanical Tire Modeling
* **Goal:** Evaluate the impact of heat buildup on tire grip and cornering stiffness during warmup cycles. The model accounts for vertical load, rolling speed, and slip frequency, integrating relaxation length for transient force build-up during steering pad and slalom maneuvers.
* **Methods/Keywords:** MF-Tyre Thermal Coupling, Heat Buildup, Grip Degradation, Cornering Stiffness Sensitivity, Slalom Maneuver.
* **Software:** MATLAB, Simulink

### 3. ABS Performance & Tire Sensitivity Analysis
* **Goal:** Quantify the sensitivity of Antilock Braking System (ABS) algorithms to variations in peak grip, longitudinal stiffness, and thermal state using a 7-DOF simulation model. Performance is evaluated via stopping distance and mean deceleration KPIs under high-slip braking.
* **Methods/Keywords:** ABS Control Logic, 7-DOF Braking Model, Sensitivity Analysis, Stopping Distance KPI, Thermal Grip Loss.
* **Software:** MATLAB, Simulink

### 4. Experimental Data Fitting & MF-Tyre 6.2 Parameter Identification
* **Goal:** Characterize an MF-Tyre 6.2 model from experimental drum testing data. Identifies lateral relaxation length via time-domain (cross-correlation) and frequency-domain (FRF) techniques, and implements custom non-linear optimization algorithms (fmincon) to fit longitudinal force, lateral force, and self-aligning torque coefficients.
* **Methods/Keywords:** MF-Tyre 6.2 Fitting, Parameter Identification, Relaxation Length (FRF & Cross-Correlation), fmincon Optimization, Camber & Pressure Sensitivity.
* **Software:** MATLAB, Simulink
