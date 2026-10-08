# Data description

This folder contains numerical data used for generating phase diagrams and
diagnostic plots for interacting disordered Majorana chains.

The data are organized by physical model and symmetry class.

## Folder structure

### `data_fully_critical_chain_BDI/`

Data for the fully critical Majorana chain in symmetry class BDI.

Typical files:

- `500_majoranas_c.npy`  
  Effective central charge map.

- `500_majoranas_cdw.npy`  
  Charge-density-wave order parameter or CDW diagnostic.

- `500_majoranas_ipr.npy`  
  Inverse participation ratio.

- `500_majoranas_agr.npy`  
  Average gap ratio.

- `500_majoranas_counts.npy`  
  Number of disorder realizations, converged points, or samples used in the averaging.

- `500_majoranas_active.npy`  
  Mask or indicator of active/converged data points.

- `500_nK_Qavg.npy`  
  Disorder-averaged momentum-space diagnostic.

- `500_nK_Q_value.npy`  
  Value of the dominant momentum-space peak.

- `500_nK_Q_idx.npy`  
  Index of the dominant momentum-space peak.

- `500_nK_Qext_value.npy`  
  Extended or auxiliary momentum-space diagnostic.

- `500_nK_env_mean.npy`  
  Mean envelope of the momentum-space occupation.

- `500_nK_curvature.npy`  
  Curvature extracted from the momentum-space occupation.

### `data_fully_critical_chain_D/`

Data for the fully critical Majorana chain in symmetry class D.

### `data_Majorana_Hubbard_chain_BDI/`

Data for the Majorana-Hubbard chain in symmetry class BDI.

### `data_Majorana_Hubbard_chain_D/`

Data for the Majorana-Hubbard chain in symmetry class D.

### `data_CDW_temperature_map_Majorana_Hubbard_chain_BDI/`

Finite-temperature charge-density-wave data for the Majorana-Hubbard chain in
symmetry class BDI.


The axes of the arrays correspond to the parameter grids used in the corresponding
calculation notebooks. See the notebooks in `plotting_mean_field/`
for the precise definitions of the disorder grid, interaction grid, temperature
grid, and chain length.

