# Subsystems Optimal Design 

**Course:** Vehicle Optimal Design | Politecnico di Milano
**Date:** September 2025 - December 2025
**Software & Tools:** MATLAB, Simulink, ADAMS Car, ALTAIR Inspire
**Key Topics:** Multi-Objective Optimization, Genetic Algorithms, Neural Networks, Topological Optimization, Reinforcement Learning

## Project Overview
This folder contains the numerical scripts and the comprehensive laboratory report detailing various optimization techniques applied to automotive sub-systems and vehicle dynamics. The overarching goal is to evaluate different algorithms in minimizing conflicting objectives (e.g., road holding vs. passenger comfort).

## Evaluated Optimization Methods & Applications

| Algorithm / Method | Automotive Application | Key Objectives & Results |
| :--- | :--- | :--- |
| **Simplex Method** | Brake Distribution | Optimized brake piston diameters to match ideal braking curves. |
| **Weighted Sum & ε-Constraint** | Passive Suspension (Quarter Car) | Extracted the Pareto optimal set balancing discomfort and road holding. |
| **Interior Point & Skyhook** | Active Suspension Control | Optimized active stiffness and damping for best vehicle comfort trade-offs. |
| **Genetic Algorithms (Dominance-based)**| Double Wishbone Geometry | Minimized Roll Center Height (RCH) and Camber Change Rate errors. |
| **Design of Experiments (DoE)** | Suspension Kinematics (ADAMS) | Full factorial optimization of hardpoints to minimize toe/camber variations. |
| **Neural Networks (MLFFN)** | Vehicle Handling Optimization | Modeled relationships between mass distribution, ARB stiffness, and lateral dynamics. |
| **Topological Optimization (SIMP)** | MacPherson Lower Control Arm | Investigated lightweight design and optimal material distribution via Altair Inspire. |
| **Reinforcement Learning (MORL-DB)** | Suspension Hardpoints | Optimized camber/toe errors evaluating strict Pareto vs. rank-based reward strategies. |

---
*For the complete mathematical derivations, algorithm configurations, and analytical results, please refer to the attached PDF report.*
