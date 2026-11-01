# Exhaust Silencer CFD & CAD Analysis

## Overview
This repository contains the computer-aided design (CAD) assembly and Computational Fluid Dynamics (CFD) simulation files for a multi-baffle exhaust silencer (muffler). The project evaluates internal flow patterns, velocity distribution, and pressure drop characteristics using Creo Parametric and ANSYS Fluent.

---

## Project Structure & Components
The CAD assembly (`1ST_ASM_ASM`) is composed of the following parametric parts:
* **`TUBE`**: The main outer cylindrical shell housing the internal flow domain.
* **`BAFFLE`**: Perforated and partition plates designed to redirect airflow, create expansion chambers, and attenuate acoustic waves.
* **`CAP`**: Inlet and outlet end caps securing the assembly and defining the flow ports.

---

## Simulation Setup (ANSYS Fluent / CFD-Post)
* **Software:** ANSYS 2026 R1 Student
* **Analysis Type:** Steady-state / Transient Fluid Flow (CFD)
* **Visualizations:** Velocity streamlines (`Streamline 1`) showing flow recirculation, expansion, and contraction across the internal baffle stages.
* **Key Metrics Monitored:** 
  * Velocity magnitude ($[m\cdot s^{-1}]$)
  * Pressure drop across inlet and outlet ports
  * Flow separation and recirculation zones within the expansion chambers

---

## Results & Observations
* The velocity streamlines indicate effective flow redirection through the baffle apertures.
* Expansion chambers successfully lower peak flow velocities, contributing to acoustic attenuation.
