# Automated Non-Uniform Non-Stationary Subdivision  
## Supplementary Data for Local Parameter Exploration

This repository contains supplementary numerical data associated with the paper:

**Automated Non-Uniform Non-Stationary Subdivision with Local Tension Control for Curves and Arbitrary-Topology Surfaces**

The files provided here contain the initial local parameter configurations used in the numerical experiments involving different sensitivity-parameter pairs \((\mu,\nu)\), together with the corresponding automatically generated configurations displayed in the manuscript.

---

## Files

### Parameter data

#### `initial_parameters_used_in_figure_all_pairs.xlsx`

This file contains the initial local parameter configurations corresponding to the configurations selected and displayed in the figures.

The data are organized according to the sensitivity-parameter pairs \((\mu,\nu)\) considered in the numerical experiments.

---

#### `initial_parameters_all_sensitivity_pairs.xlsx`

This file contains the complete set of initial local parameter configurations generated for all tested sensitivity-parameter pairs.

These data were used for the automated exploration of the local parameter space.

---

## Generated configurations

The repository also contains the graphical results corresponding to the following sensitivity-parameter pairs:

- \((\mu,\nu)=(1,0)\)
- \((\mu,\nu)=(1,1)\)
- \((\mu,\nu)=(0,2)\)
- \((\mu,\nu)=(1,2)\)
- \((\mu,\nu)=(0,3)\)

For each pair, 60 automatically generated configurations are displayed.

The colors used in the figures indicate the local geometric behavior associated with the initial parameters:

- **Blue:** trigonometric
- **Green:** polynomial
- **Red:** hyperbolic

The labels \(C1,\ldots,C60\) identify the generated configurations.


