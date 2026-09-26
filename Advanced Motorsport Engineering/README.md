# Advanced Motorsport Engineering - Laboratory Projects

- **Course:** Advanced Motorsport Engineering | Politecnico di Milano
- **Instructors:** Prof. M. Gobbi, Prof. S. Melzi
- **Academic Year:** 2025 - 2026

## Course Overview
This folder contains the numerical simulations, lap time analyses, and telemetry reports developed for the *Advanced Motorsport Engineering* course. The report covers a comprehensive race engineering workflow: from fundamental vehicle performance calculations and tire thermal modeling, to advanced lap time simulations (via OpenLAP and VI-CRT) and real-world telemetry data analysis (WinTax). The goal is to optimize race vehicle setup, aerodynamics, and race strategies while adhering to thermal, dynamic, and energy constraints.

---

## 🔬 Laboratory Activities & Projects

### 0. Fundamentals of Motorsport Performance
* **Goal:** Review fundamental motorsport calculations, estimating cornering speeds (with/without aero), calculating load transfers under braking, and performing coast-down analysis to identify drag and rolling resistance.
* **Methods/Keywords:** Cornering Speed, Friction Limit, Coast-Down Test, Load Transfer, Aerodynamic Balance.
* **Software:** MATLAB

### 1. Tire Thermal Modeling & Grip Estimation
* **Goal:** Analyze the influence of vehicle setup (toe angle, aero balance, weight distribution) on tire warm-up and temperature evolution. The second phase estimates a friction law based on slip speed and tread temperature, comparing Response Surface Models and Neural Networks.
* **Methods/Keywords:** Tire Warm-Up, Thermal Model, Friction Law, Response Surface Modeling, Neural Network.
* **Software:** MATLAB, Set4T

### 2. Lap Time Simulation & Aerodynamic Setup
* **Goal:** Evaluate the performance of a Tatuus FA010 vehicle using a point-mass lap time simulator. The study quantifies fuel mass penalties and builds isochrone maps to identify the optimal drag-to-downforce trade-off for different track layouts.
* **Methods/Keywords:** Lap Time Simulation, Point-Mass Model, Isochrone Maps, Aerodynamic Setup, Fuel Load.
* **Software:** MATLAB, OpenLAP

### 3. Braking System Sizing (Brembo)
* **Goal:** Size a formula vehicle's braking system combining thermal and dynamic constraints. Focuses on brake disc selection for optimal stint temperatures, defining hydraulic brake balance, and evaluating performance via a bicycle model at Monza.
* **Methods/Keywords:** Brake Disc Sizing, Thermal Model, Brake Balance, Line Pressure, Bicycle Model.
* **Software:** MATLAB, OpenLAP

### 4. Advanced Lap Time Simulation: Aero Maps & Race Strategy
* **Goal:** Extend lap time simulations to include ride-height-dependent aerodynamics and race strategies. Evaluates the impact of ground stiffness/ride height on aero coefficients and analyzes Lift-and-Coast strategies at Monza for fuel saving and brake energy reduction.
* **Methods/Keywords:** Ride Height, Aerodynamic Maps, Lift and Coast, Fuel Saving, Race Simulation.
* **Software:** MATLAB, OpenLAP

### 5. Telemetry Data Analysis (Magneti Marelli WinTax)
* **Goal:** Analyze racing motorcycle telemetry focusing on acceleration signals from Mugello and Phillip Island. Involves virtual channel definition, coordinate transformation (IMU to inertial frame), and signal filtering to identify peak lateral accelerations.
* **Methods/Keywords:** Telemetry Analysis, Motorcycle Dynamics, IMU, Coordinate Transformation, Signal Filtering.
* **Software:** WinTax

### 6. Optimal Control & Energy Management
* **Goal:** Solve a minimum lap time optimal control problem focusing on energy constraints (10 MJ vs 12 MJ vs 15 MJ). The analysis highlights how racing trajectories and driver inputs adapt (e.g., earlier lift-off, extended coasting) under strict energy limits.
* **Methods/Keywords:** Optimal Control, Energy Constraint, Lift and Coast, Minimum Lap Time, Racing Trajectory.
* **Software:** MATLAB

### 7. VI-CRT Setup Analysis & Simulation
* **Goal:** Perform a setup analysis of a Dallara F312 using VI-grade tools. Evaluates the impact of gear ratios, downforce, and anti-roll bar stiffness via telemetry comparison. A final DoE investigates spring stiffness trends for lap time optimization.
* **Methods/Keywords:** Setup Analysis, Telemetry Comparison, Understeer Gradient, Design of Experiments (DoE), Spring Stiffness.
* **Software:** VI-CRT / VI-grade, MATLAB

### Motorsport Seminars
* **Goal:** Integration of professional motorsport insights covering race engineering, sustainability, Formula 1 setup strategies, tire design (racing and cycling), motorcycle simulation, and electric motor hardware for racing applications.
* **Methods/Keywords:** Race Engineering, F1 Setup, Sustainability, Motorsport Technology, Electric Motors.
