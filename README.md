# MaroFlux PDE-ODE Hybrid Simulation Suite

**A Unified Mathematical and Geochemical Framework for Temporally-Programmed Immunomodulatory Bioceramics and Neuromuscular Regeneration**

> **Author:** Marwan Alaa Mohamed Mohamed Raslan  
> **Affiliation:** Independent Researcher, Cairo, Egypt  
> **Manuscript:** *MaroFlux_Final_v6.pdf* — Theoretical & Computational Framework  
> **Article Type:** Comprehensive Theory and Perspective  
> **License:** MIT  
> **Zenodo DOI:** [`10.5281/zenodo.20135313`](https://doi.org/10.5281/zenodo.20135313)

---

## 📋 Overview

This repository contains the complete computational reproducibility package for the **MaroFlux Paradigm** manuscript. All simulation code, calibrated parameters, and sensitivity results are provided to enable full independent verification of the theoretical claims.

The codebase implements:
- **PDE solver** (Implicit Backward Euler, Sec 3.7.1) for spatiotemporal ion transport
- **ODE solver** (LSODA, Sec 3.2) for macrophage polarization and muscle dynamics
- **Strang splitting** coupling scheme with O(Δt²) verified accuracy (Sec 3.7.3)
- **Bifurcation analysis** (Sec 3.3.3) — saddle-node threshold for k_gate
- **Sobol sensitivity analysis** (Sec 3.4.2) via Saltelli sampling
- **Monte Carlo UQ** (Sec 3.4.3) — 95% confidence intervals on all key outputs
- **6-panel publication figure** matching manuscript methodology

---

## 🗂️ Repository Structure
