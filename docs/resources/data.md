# Input Forcing Datasets & Code Repository

DesertMIP is strongly committed to open science. We provide high-fidelity, spatiotemporally dynamic boundary condition datasets to the global climate modeling community to facilitate the execution of our experimental protocol.

## Official Forcing Datasets

Our primary scientific output for Earth System Model (ESM) developers is the **DesertMIP Transient Boundary Dataset (v1.0)**. 

### Dataset Specifications
* **Spatial Resolution:** Native $0.25^\circ \times 0.25^\circ$ (with conservative regridding tools available for standard CMIP resolutions).
* **Temporal Resolution:** Monthly transient states (capturing seasonal and interannual boundary shifts).
* **Format:** NetCDF4 (Strictly CF-compliant).
* **Methodology:** This dataset is derived from a synergetic combination of high-resolution Earth Observation records (e.g., ESA WorldCover, MODIS) and advanced predictive algorithms forecasting future expansion/contraction under distinct Shared Socioeconomic Pathways (SSPs).

## Data Access Pathways

The forcing datasets for Tier-1 transient experiments are currently undergoing final internal validation and spatial smoothing to prevent numerical shocks in coupled models. 

Upon the publication of our experimental design protocol in *Geoscientific Model Development (GMD)*, the fully vetted datasets will be distributed via:
1. **Primary Node:** Earth System Grid Federation (ESGF) input data directory.
2. **Secondary Mirror:** Zenodo repository (assigned with a permanent DOI for proper academic citation and persistent access).

## Open-Source Code Repository

All algorithmic frameworks, pre-processing utilities, and dynamic boundary generation scripts curated by the DesertMIP Steering Committee are entirely open-source. 

We provide these tools under an MIT License via our **GitHub Organization**. Modeling groups are encouraged to utilize our scalable pipelines to confidently regrid and ingest the dynamic forcing files into their native ESM grids:

* **Interpolation Scripts:** Mass- and energy-conserving regridding utilities.
* **Evaluation Notebooks:** Jupyter notebooks for offline verification of the forcing data prior to fully coupled execution.

For access to the code base and detailed technical documentation, please visit the [DesertMIP GitHub Repository](https://github.com/EarthSystemSci/DesertMIP).
