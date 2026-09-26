# Vehicle Optimal Design - Laboratory Projects

- **Course:** Vehicle Optimal Design | Politecnico di Milano 
- **Instructors:** Prof. M. Gobbi, Eng. P. Stabile 
- **Academic Year:** 2025 - 2026 

## Course Overview
This folder contains the laboratory reports and numerical models developed for the *Vehicle Optimal Design* course. The project focuses on applying advanced mathematical optimization techniques to solve complex engineering problems related to vehicle subsystems design. The goal is to evaluate single and multi-objective optimization algorithms to find the best trade-offs in conflicting vehicle dynamics metrics.

---

## 🔬 Laboratory Activities & Projects

### 1. Brake Distribution
* **Goal:** Optimize the braking distribution of a simplified car model by varying brake piston diameters to minimize the error between ideal and real braking curves.
* **Methods/Keywords:** Simplex Method, `fminsearch`, Piston Area Ratio, Well-Posedness.
* **Software:** MATLAB

### 2 & 3. Passive Suspension Optimization
* **Goal:** Optimize a passive suspension system by identifying the Pareto optimal set between two conflicting objectives: minimizing passenger discomfort and maximizing road holding (Quarter Car Model).
* **Methods/Keywords:** Multi-Objective Optimization, Weighted Sum Method, ε-Constraints Method, Fritz John Conditions.
* **Software:** MATLAB

### 4 & 5. Active Suspension (Skyhook Control)
* **Goal:** Optimize an active suspension system using a Skyhook control strategy to find the best trade-off between road holding and discomfort.
* **Methods/Keywords:** Interior Point Algorithm, ε-Constraints Method, Pareto Optimal Set, Active vs Passive Comparison.
* **Software:** MATLAB

### 6 & 7. Genetic Algorithms & Double Wishbone Kinematics
* **Goal:** Implement a genetic algorithm to solve minimization problems, followed by the geometric optimization of a double wishbone suspension to minimize Roll Center Height (RCH) and Camber Change Rate errors.
* **Methods/Keywords:** Genetic Algorithms (Mutation, Crossover, Elitism), Sensitivity Analysis, Dominance-Based Ranking, Pareto Front.
* **Software:** MATLAB

### 8. Design Of Experiments (DoE) - Suspension Hardpoints
* **Goal:** Investigate the impact of suspension hardpoint coordinates on vehicle behavior. Optimize kinematic parameters to minimize camber/toe variations and dynamic parameters to reduce roll angle and yaw rate during a step steer maneuver.
* **Methods/Keywords:** Full Factorial Design of Experiments (DoE), Multibody Simulation, Response Surface.
* **Software:** ADAMS Car, ADAMS Insight

### 9 & 10. Artificial Neural Networks (ANN) - Handling Optimization
* **Goal:** Train a Multi-Layer Feedforward Network (MLFFN) to model non-linear relationships between mass distribution, anti-roll bar stiffness, and stability metrics. The ANN is then used to predict lateral acceleration and yaw rate variations to optimize vehicle handling.
* **Methods/Keywords:** Sensitivity Analysis, Fractional Factorial Design, Back-propagation, Spearman Correlation.
* **Software:** MATLAB, Vi-CarRealTime

### 11. Topological Optimization - MacPherson Suspension
* **Goal:** Investigate topological optimization as a methodology for lightweight vehicle design, focusing on structural efficiency and material distribution of a MacPherson lower control arm.
* **Methods/Keywords:** SIMP Algorithm, Lightweight Design, Finite Element Method (FEM).
* **Software:** MATLAB, ALTAIR Inspire

### 12. Reinforcement Learning - Suspension Design
* **Goal:** Apply Reinforcement Learning (RL) to optimize the hardpoint coordinates of a double wishbone suspension system, targeting minimized errors in camber and toe.
* **Methods/Keywords:** MORL-DB Algorithm, Reward Function Design, Pareto Dominance.
* **Software:** MATLAB, Simulink
