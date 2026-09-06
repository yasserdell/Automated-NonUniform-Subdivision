# Automated Non-Uniform Non-Stationary Subdivision

## Supplementary Data for Local Parameter Exploration

This repository contains supplementary numerical data associated with the paper:

**Automated Non-Uniform Non-Stationary Subdivision with Local Tension Control for Curves and Arbitrary-Topology Surfaces**

The files provided here contain the initial local parameter configurations used in the numerical experiments for different sensitivity-parameter pairs $(\mu,\nu)$, together with the corresponding generated configurations and selected tensor-product surfaces.

---

## Files

### Parameter data

#### `initial_parameters_used_in_figure_all_pairs.xlsx`

This file contains the initial local parameter configurations corresponding to the configurations selected and displayed in the manuscript figures.

The data are organized according to the sensitivity-parameter pairs $(\mu,\nu)$ considered in the numerical experiments.

#### `initial_parameters_all_sensitivity_pairs.xlsx`

This file contains the complete set of initial local parameter configurations generated for all tested sensitivity-parameter pairs.

These data were used for the automated exploration of the local parameter space.

---

## Generated configurations

The repository contains graphical results for the following sensitivity-parameter pairs:

- $(\mu,\nu)=(1,0)$
- $(\mu,\nu)=(1,1)$
- $(\mu,\nu)=(0,2)$
- $(\mu,\nu)=(1,2)$
- $(\mu,\nu)=(0,3)$

For each pair, 60 automatically generated configurations are displayed.

The corresponding files are:

- `case_mu1_nu0_60_configurations.png`
- `case_mu1_nu1_60_configurations.png`
- `case_mu0_nu2_60_configurations.png`
- `case_mu1_nu2_60_configurations.png`
- `case_mu0_nu3_60_configurations.png`

The colors used in the figures indicate the local geometric behavior associated with the initial parameters:

- **Blue:** trigonometric
- **Green:** polynomial
- **Red:** hyperbolic

The labels `C1` to `C60` identify the generated configurations.

---

## Selected tensor-product surfaces

#### `surfaces_selected.png`

This figure shows representative tensor-product surfaces obtained from selected automatically generated local parameter configurations.

It illustrates how different local parameter distributions can produce different geometric behaviors within the same subdivision framework.

---

## Reproducibility

The Excel files provide the initial local parameter values used in the numerical experiments.

Once an initial local parameter configuration is selected, the parameter values at subsequent subdivision levels are computed analytically using the half-angle recurrence defined in the paper.

The automated procedure is therefore used only to generate or select admissible initial parameter configurations, while the subsequent subdivision process remains entirely analytical.

---

## Purpose

The purpose of these supplementary data is to provide the numerical parameter configurations associated with the examples presented in the paper and to facilitate the reproduction and further analysis of the reported results.

---
